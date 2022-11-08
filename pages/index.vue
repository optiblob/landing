<template>
  <div>
    <div class="">
      <div class="relative overflow-hidden">
        <div class="absolute inset-y-0 h-full w-full" aria-hidden="true">
          <div class="relative h-full">
            <svg
              class="absolute right-full translate-y-1/3 translate-x-1/4 transform sm:translate-x-1/2 md:translate-y-1/2 lg:translate-x-full"
              width="404" height="784" fill="none" viewBox="0 0 404 784">
              <defs>
                <pattern id="e229dbec-10e9-49ee-8ec3-0286ca089edf" x="0" y="0" width="20" height="20"
                         patternUnits="userSpaceOnUse">
                  <rect x="0" y="0" width="4" height="4" class="text-gray-200" fill="currentColor"/>
                </pattern>
              </defs>
              <rect width="404" height="784" fill="url(#e229dbec-10e9-49ee-8ec3-0286ca089edf)"/>
            </svg>
            <svg
              class="absolute left-full -translate-y-3/4 -translate-x-1/4 transform sm:-translate-x-1/2 md:-translate-y-1/2 lg:-translate-x-3/4"
              width="404" height="784" fill="none" viewBox="0 0 404 784">
              <defs>
                <pattern id="d2a68204-c383-44b1-b99f-42ccff4e5365" x="0" y="0" width="20" height="20"
                         patternUnits="userSpaceOnUse">
                  <rect x="0" y="0" width="4" height="4" class="text-gray-200" fill="currentColor"/>
                </pattern>
              </defs>
              <rect width="404" height="784" fill="url(#d2a68204-c383-44b1-b99f-42ccff4e5365)"/>
            </svg>
          </div>
        </div>


        <div class="relative bg-gray-50 pt-6 pb-16 sm:pb-24">
          <div>
            <div class="mx-auto max-w-7xl px-4 sm:px-6">
              <nav class="relative flex items-center justify-between sm:h-10 md:justify-center" aria-label="Global">
                <div class="flex flex-1 items-center md:absolute md:inset-y-0 md:left-0">
                  <div class="flex w-full items-center justify-between md:w-auto">
                    <a href="#">
                      <span class="sr-only">Your Company</span>
                      <img src="../static/logo.png" class="h-10" alt="">
                    </a>
                    <div class="-mr-2 flex items-center md:hidden">
                      <button type="button"
                              class="inline-flex items-center justify-center rounded-md bg-gray-50 p-2 text-gray-400 hover:bg-gray-100 hover:text-gray-500 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500"
                              aria-expanded="false">
                        <span class="sr-only">Open main menu</span>
                        <!-- Heroicon name: outline/bars-3 -->
                        <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                             stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                          <path stroke-linecap="round" stroke-linejoin="round"
                                d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"/>
                        </svg>
                      </button>
                    </div>
                  </div>
                </div>
                <div class="hidden md:flex md:space-x-10">
                  <a href="#" class="font-medium text-gray-500 hover:text-gray-900">Product</a>

                  <a href="#" class="font-medium text-gray-500 hover:text-gray-900">Features</a>

                  <a href="#" class="font-medium text-gray-500 hover:text-gray-900">Marketplace</a>

                  <a href="#" class="font-medium text-gray-500 hover:text-gray-900">Company</a>
                </div>
                <div class="hidden md:absolute md:inset-y-0 md:right-0 md:flex md:items-center md:justify-end">
              <span class="inline-flex rounded-md shadow">
                <a href="https://app.optiblob.com"
                   target="_blank"
                   class="inline-flex items-center rounded-md border border-transparent bg-white px-4 py-2 text-base font-medium text-indigo-600 hover:text-indigo-500">Accéder à la plateforme</a>
              </span>
                </div>
              </nav>
            </div>

            <!--
              Mobile menu, show/hide based on menu open state.

              Entering: "duration-150 ease-out"
                From: "opacity-0 scale-95"
                To: "opacity-100 scale-100"
              Leaving: "duration-100 ease-in"
                From: "opacity-100 scale-100"
                To: "opacity-0 scale-95"
            -->
            <div class="absolute inset-x-0 top-0 z-10 origin-top-right transform p-2 transition md:hidden">
              <div class="overflow-hidden rounded-lg bg-white shadow-md ring-1 ring-black ring-opacity-5">
                <div class="flex items-center justify-between px-5 pt-4">
                  <div>
                    <img class="h-8 w-auto" src="https://tailwindui.com/img/logos/mark.svg?color=indigo&shade=600"
                         alt="">
                  </div>
                  <div class="-mr-2">
                    <button type="button"
                            class="inline-flex items-center justify-center rounded-md bg-white p-2 text-gray-400 hover:bg-gray-100 hover:text-gray-500 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500">
                      <span class="sr-only">Close main menu</span>
                      <!-- Heroicon name: outline/x-mark -->
                      <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                           stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/>
                      </svg>
                    </button>
                  </div>
                </div>
                <div class="space-y-1 px-2 pt-2 pb-3">
                  <a href="#"
                     class="block rounded-md px-3 py-2 text-base font-medium text-gray-700 hover:bg-gray-50 hover:text-gray-900">Product</a>

                  <a href="#"
                     class="block rounded-md px-3 py-2 text-base font-medium text-gray-700 hover:bg-gray-50 hover:text-gray-900">Features</a>

                  <a href="#"
                     class="block rounded-md px-3 py-2 text-base font-medium text-gray-700 hover:bg-gray-50 hover:text-gray-900">Marketplace</a>

                  <a href="#"
                     class="block rounded-md px-3 py-2 text-base font-medium text-gray-700 hover:bg-gray-50 hover:text-gray-900">Company</a>
                </div>
                <a href="#"
                   class="block w-full bg-gray-50 px-5 py-3 text-center font-medium text-indigo-600 hover:bg-gray-100 hover:text-indigo-700">Log
                  in</a>
              </div>
            </div>
          </div>

          <div class="mx-auto mt-16 max-w-7xl px-4 sm:mt-24 sm:px-6">
            <div class="text-center">
              <h1
                class="text-4xl font-bold flex flex-row justify-center tracking-tight text-gray-900 sm:text-5xl md:text-6xl">
                <span class="block">OPTI</span>
                <span class="block text-indigo-600">BLOB</span>
              </h1>
              <p class="mx-auto mt-3 max-w-md text-base text-gray-500 sm:text-lg md:mt-5 md:max-w-3xl md:text-xl">Un <b>blob</b>
                pour optimiser l'électricité du futur et le <b>V2G</b> pour la partager.</p>
            </div>
          </div>
        </div>

        <div class="relative bg-gray-50 pb-10">
          <div class="lg:mx-auto lg:grid lg:max-w-7xl lg:grid-cols-2 lg:items-start lg:gap-24 lg:px-8">
            <div class="relative sm:py-16 lg:py-0">
              <div aria-hidden="true" class="hidden sm:block lg:absolute lg:inset-y-0 lg:right-0 lg:w-screen">
                <div class="absolute inset-y-0 right-1/2 w-full rounded-r-3xl bg-white lg:right-72"></div>
                <svg class="absolute top-8 left-1/2 -ml-3 lg:-right-8 lg:left-auto lg:top-12" width="404" height="392" fill="none" viewBox="0 0 404 392">
                  <defs>
                    <pattern id="02f20b47-fd69-4224-a62a-4c9de5c763f7" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
                      <rect x="0" y="0" width="4" height="4" class="text-gray-200" fill="currentColor" />
                    </pattern>
                  </defs>
                  <rect width="404" height="392" fill="url(#02f20b47-fd69-4224-a62a-4c9de5c763f7)" />
                </svg>
              </div>
              <div class="relative mx-auto max-w-md px-4 sm:max-w-3xl sm:px-6 lg:max-w-none lg:px-0 lg:py-20">
                <!-- Testimonial card-->
                <div class="relative overflow-hidden rounded-2xl shadow-xl">
                  <img class="h-full w-full" src="../static/Map-des-lignes-hautes-tensions-de-france.png" alt="">
                </div>
              </div>
            </div>

            <div class="relative mx-auto max-w-md px-4 sm:max-w-3xl sm:px-6 lg:px-0">
              <!-- Content area -->
              <div class="pt-20">
                <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Optimisation des pertes</h2>
                <div class="mt-2 space-y-6 text-gray-500 text-justify">
                  <p class="text-base">Un réseau optimal doit satisfaire à plusieurs contraintes : minimiser les pertes ohmiques, réduire le coût de construction et assurer aux destinataires la puissance dont ils ont besoin, même en cas d'anomalie partielle sur le réseau.</p>
                  <p class="text-base leading-7">La demande en électricité varie en permanence au cours d'une journée, selon les horaires de travail, les besoins en chauffage, les grands événements publics, etc. L'électricité produite par les centrales nucléaires doit s'ajuster en temps réel à la consommation des utilisateurs. Pour cela le réseau s'appuie sur des centres de répartition de l'électricité : les dispatchings.</p>
                  <p class="text-base leading-7">Ces dispatchings sont interconnectés par des lignes à hautes tensions. Ces lignes induisent des pertes et leurs maillages doivent être optimisés pour en éviter un maximum.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="bg-gray-50 pt-2">
          <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
            <div class="mx-auto max-w-4xl text-center">
              <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">L'éléctricité Française est avant tout nucléaire.</h2>
            </div>
          </div>
          <div class="mt-10 bg-white pb-12 sm:pb-16">
            <div class="relative">
              <div class="absolute inset-0 h-1/2 bg-gray-50"></div>
              <div class="relative mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
                <div class="mx-auto max-w-5xl">
                  <dl class="rounded-lg bg-white shadow-lg sm:grid sm:grid-cols-4">
                    <div class="flex flex-col border-b border-gray-100 p-6 text-center sm:border-0 sm:border-r">
                      <dd class="text-5xl font-bold tracking-tight text-indigo-600">70%</dd>
                      <dt class="mt-2 text-lg font-medium leading-6 text-gray-500">de production nucléaire</dt>
                    </div>
                    <div class="flex flex-col border-t border-b border-gray-100 p-6 text-center sm:border-0 sm:border-l sm:border-r">
                      <dd class="text-5xl font-bold tracking-tight text-indigo-600">360</dd>
                      <dt class="mt-2 text-lg font-medium leading-6 text-gray-500">Twh produits en 2021</dt>
                    </div>
                    <div class="flex flex-col border-t border-b border-gray-100 p-6 text-center sm:border-0 sm:border-l sm:border-r">
                      <dd class="text-5xl font-bold tracking-tight text-indigo-600">6 à 10%</dd>
                      <dt class="mt-2 text-lg font-medium leading-6 text-gray-500">de perte sur le réseau</dt>
                    </div>
                    <div class="flex flex-col border-t border-gray-100 p-6 text-center sm:border-0 sm:border-l">
                      <dd class="text-5xl font-bold tracking-tight text-indigo-600">56</dd>
                      <dt class="mt-2 text-lg font-medium leading-6 text-gray-500">réacteurs nucléaires</dt>
                    </div>
                  </dl>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="relative bg-white py-16">
          <div class="absolute inset-x-0 top-0 hidden h-1/2 lg:block" aria-hidden="true"></div>
          <div class="mx-auto max-w-7xl bg-indigo-600 lg:bg-transparent lg:px-8">
            <div class="lg:grid lg:grid-cols-12">
              <div class="relative z-10 lg:col-span-4 lg:col-start-1 lg:row-start-1 lg:bg-transparent lg:py-16">
                <div class="absolute inset-x-0 h-1/2 lg:hidden" aria-hidden="true"></div>
                <div class="mx-auto max-w-md px-4 sm:max-w-3xl sm:px-6 lg:max-w-none lg:p-0">
                  <div class="aspect-w-10 aspect-h-6 sm:aspect-w-2 sm:aspect-h-1 lg:aspect-w-1">
                    <img class="rounded-3xl object-cover object-center shadow-2xl" src="../static/blobnetwork.gif" alt="">
                  </div>
                </div>
              </div>

              <div class="relative bg-indigo-600 lg:col-span-10 lg:col-start-3 lg:row-start-1 lg:grid lg:grid-cols-10 lg:items-center lg:rounded-3xl">
                <div class="absolute inset-0 hidden overflow-hidden rounded-3xl lg:block" aria-hidden="true">
                  <svg class="absolute bottom-full left-full translate-y-1/3 -translate-x-2/3 transform xl:bottom-auto xl:top-0 xl:translate-y-0" width="404" height="384" fill="none" viewBox="0 0 404 384" aria-hidden="true">
                    <defs>
                      <pattern id="64e643ad-2176-4f86-b3d7-f2c5da3b6a6d" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
                        <rect x="0" y="0" width="4" height="4" class="text-indigo-500" fill="currentColor" />
                      </pattern>
                    </defs>
                    <rect width="404" height="384" fill="url(#64e643ad-2176-4f86-b3d7-f2c5da3b6a6d)" />
                  </svg>
                  <svg class="absolute top-full -translate-y-1/3 -translate-x-1/3 transform xl:-translate-y-1/2" width="404" height="384" fill="none" viewBox="0 0 404 384" aria-hidden="true">
                    <defs>
                      <pattern id="64e643ad-2176-4f86-b3d7-f2c5da3b6a6d" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
                        <rect x="0" y="0" width="4" height="4" class="text-indigo-500" fill="currentColor" />
                      </pattern>
                    </defs>
                    <rect width="404" height="384" fill="url(#64e643ad-2176-4f86-b3d7-f2c5da3b6a6d)" />
                  </svg>
                </div>
                <div class="relative mx-auto max-w-md space-y-6 py-12 px-4 sm:max-w-3xl sm:py-16 sm:px-6 lg:col-span-6 lg:col-start-4 lg:max-w-none lg:p-0 text-justify">
<!--                  <p class="text-base text-white leading-7"></p>-->
<!--                  <p class="text-base text-white leading-7">En fonction de l'existant, il sera possible de corriger aux mieux les interconnexions existantes avec celles proposées par le blob. Voir-->
<!--                    <a class="text-indigo-500 font-medium" href="https://www.researchgate.net/figure/Comparison-of-the-Physarum-networks-with-the-Tokyo-rail-network-A-In-the-absence-of_fig2_41111573" target="_blank">Physarum Network</a>.</p>-->
                  <h2 class="text-3xl font-bold tracking-tight text-white" id="join-heading">Le blob</h2>
                  <p class="text-lg text-white">un organisme monocellulaire vivant en se servant du principe d’optimisation des chemins les plus courts entre ses points de nourriture. De ce constat nous allons recréer l’interconnexion des centres de répartition électriques avec une optimisation de ces chemins.</p>
                  <p class="text-lg text-white">En fonction de l'existant, il sera possible de corriger aux mieux les interconnexions présentes avec celles proposées par le blob. Pour en savoir plus, le bouton ci-dessous vous informe sur le Physarum Network.</p>
                  <a class="block w-full rounded-md border border-transparent bg-white py-3 px-5 text-center text-base font-medium text-indigo-700 shadow-md hover sm:inline-block sm:w-auto" href="https://www.researchgate.net/figure/Comparison-of-the-Physarum-networks-with-the-Tokyo-rail-network-A-In-the-absence-of_fig2_41111573" target="_blank">En savoir plus</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="relative bg-white pt-40">
          <div class="absolute inset-0 flex flex-col" aria-hidden="true">
            <div class="flex-1 bg-white"></div>
            <div class="w-full flex-1 bg-indigo-600"></div>
          </div>
          <div class="mx-auto max-w-7xl flex justify-center px-4 sm:px-6">
            <div class="h-[500px] w-[500px] mt-1 z-50 flex justify-center items-center drop-shadow-xl">
              <video
                src="../static/Algorithm-imitating-the-behavior-of-a-blob-to-link-the-nuclear-power-plants-of-France.mp4"
                class="relative h-full w-full rounded-l-xl" autoplay muted loop></video>
              <img src="../static/Schema-de-l-algorythme.jpg" class="h-full -mx-1" alt="">
              <div class="w-[500px] rounded-r-xl">
                <pre><code class="language-python">
# UTF8 encoding
"""
Physarum simulation

Based on the work of Jeff Jones, UWE https://uwe-repository.worktribe.com/output/980579
and Sage Jensen https://sagejenson.com/physarum

@authors:
 - LE RAY Arthur
 - GILLET Kévin
 - RIBREAU Augustin
"""

# handle imports
import numpy as np
import matplotlib.pyplot as plt
import random
from scipy import ndimage
import matplotlib.animation as animation  # only needed if you want to make an animation

# France nuclear powerplant locations. Based on a 200x200 pixel france map.
locations = [
    [51, 49],   # Flamanville
    [82, 42],   # Paluel
    [90, 40],   # Penly
    [100, 20],  # Gravelines
    [134, 38],  # Chooz
    [152, 51],  # Cattenom
    [118, 68],  # Nogent
    [105, 82],  # Dampierre
    [95, 83],   # Saint-Laurent
    [77, 92],   # Chinon
    [83, 106],  # Civaux
    [112, 87],  # Belleville
    [66, 127],  # Le Blayais
    [86, 148],  # Golfech
    [133, 143], # Tricastin
    [134, 138], # Cruas
    [134, 125], # St-Alban
    [140, 117]  # Bugey
]


class Environment:
    def __init__(self, N=200, M=200, pp=0.15):
        '''
        pp = percentage of the map size to generate population. default 15% - 6000 particles in 200x200 environment
        '''
        self.N = N
        self.M = M
        self.data_map = np.zeros(shape=(N, M))
        self.trail_map = np.zeros(shape=(N, M))
        self.population = int((self.N * self.M) * (pp))
        self.particles = []  # holds particles

    def populate(self, SA=np.pi / 4, RA=np.pi / 8, SO=9):
        '''
        randomly populates pp% of the map with particles of:
        SA = Sensor Angle
        RA = Rotation Angle
        SO = Sensor Offset
        '''
        while (np.sum(self.data_map) < self.population):   # loop until population size met
            rN = np.random.randint(self.N)
            rM = np.random.randint(self.M)
            if (self.data_map[rN,rM] == 0):
                p = Particle((rN,rM),SA,RA,SO)
                self.particles.append(p)   # list holds particle and its position
                self.data_map[rN,rM] = 1   # assign a value of 1 to the particle location
            else:
                pass

        for location in locations:
          self.deposit_food((location[1], location[0]))

    def deposit_food(self, pos, strength=3, rad=6):
        '''
        applies a circular distribution of food to the trail map
        '''

        n, m = pos  # location of food
        y, x = np.ogrid[-n:self.N - n, -m:self.M - m]  # work directly on pixels of the trail map
        mask = x ** 2 + y ** 2 <= rad ** 2  # create circular mask of desired radius
        self.trail_map[mask] = strength

    def diffusion_operator(self, const=0.6, sigma=2):
        '''
        applies a Gaussian filter to the entire trail map, spreading out chemoattractant
        const multiplier controls decay rate (lower = greater rate of decay, keep <1)
        Credit to: https://github.com/ecbaum/physarum/blob/8280cd131b68ed8dff2f0af58ca5685989b8cce7/species.py#L52
        '''
        self.trail_map = const * ndimage.gaussian_filter(self.trail_map, sigma)

    def check_surroundings(self, point, angle):
        '''
        Helper function for motor_stage()
        Determines if the adjacent spot in the data map is available, based on particle angle
        '''
        n, m = point
        x = np.cos(angle)
        y = np.sin(angle)
        # periodic BCs -> %
        if (self.data_map[(n - round(x)) % self.N, (m + round(y)) % self.M] == 0):  # position unoccupied, move there
            return ((n - round(x)) % self.N, (m + round(y)) % self.M)
        elif (self.data_map[(n - round(x)) % self.N, (m + round(y)) % self.M] == 1):  # position occupied, stay
            return point

    def motor_stage(self):
        '''
        Scheduler function - causes every particle in population to undergo motor stage
        Particles randomly sampled to avoid long-term bias from sequential ordering
        '''
        rand_order = random.sample(self.particles, len(self.particles))
        for i in range(len(rand_order)):
            old_x, old_y = rand_order[i].pos
            new_x, new_y = self.check_surroundings(rand_order[i].pos, rand_order[i].phi)
            if ((new_x, new_y) == (old_x, old_y)):  # move invalid, stay and choose new orientation, update sensors
                rand_order[i].phi = 2 * np.pi * np.random.random()
                rand_order[i].update_sensors()
            else:  # move valid: move there, change value in data map accordingly, deposit trail, AND change particle position
                rand_order[i].pos = (new_x, new_y)
                rand_order[i].update_sensors()
                self.data_map[old_x, old_y] = 0
                self.data_map[new_x, new_y] = 1
                rand_order[i].deposit_phermone_trail(self.trail_map)

    def sensory_stage(self):
        '''
        Makes every particle undergo sensory stage in random order
        '''
        rand_order = random.sample(self.particles, len(self.particles))
        for i in range(len(rand_order)):
            rand_order[i].sense(self.trail_map)


class Particle:
    def __init__(self, pos, SA=np.pi / 8, RA=np.pi / 4, SO=3.):
        '''
        Initializes physical characteristics of the particle
        pos = (n,m) in data map
        phi = initial random angle of orientation of the particle [0,2pi]
        SA = +- sensor angle wrt phi
        SO = sensor offset from body
        SS = step size - DONT USE
        RA = rotation angle of particle
        '''
        self.pos = pos
        self.phi = 2 * np.pi * np.random.random()
        self.SA = SA
        self.RA = RA
        self.SO = SO
        # initialize sensor angles wrt body - will be updated as particle moves
        self.phi_L = self.phi - SA  # left sensor
        self.phi_C = self.phi  # center sensor  - probably redundant, can just use self.phi
        self.phi_R = self.phi + SA  # right sensor

    def deposit_phermone_trail(self, arr, strength=1.):
        '''
        Applies a single trail of chemoattractant at current position
        '''
        n, m = self.pos
        arr[n, m] = strength

    def update_sensors(self):
        '''
        Updates the sensor positions relative to the particle's orientation
        (Left, Center, Right)
        '''
        self.phi_L = self.phi - self.SA
        self.phi_C = self.phi
        self.phi_R = self.phi + self.SA

    def get_sensor_values(self, arr):
        '''
        Finds the value of the chemoattractant at each of the 3 sensors
        Pass the TrailMap array as an argument
        '''
        n, m = self.pos
        row, col = arr.shape

        xL = round(self.SO * np.cos(self.phi_L))
        yL = round(self.SO * np.sin(self.phi_L))
        xC = round(self.SO * np.cos(self.phi_C))
        yC = round(self.SO * np.sin(self.phi_C))
        xR = round(self.SO * np.cos(self.phi_R))
        yR = round(self.SO * np.sin(self.phi_R))

        # implement periodic BCs
        valL = arr[(n - xL) % row, (m + yL) % col]
        valC = arr[(n - xC) % row, (m + yC) % col]
        valR = arr[(n - xR) % row, (m + yR) % col]

        return (valL, valC, valR)

    def sense(self, arr):
        '''
        The particle reads from the trail map, rotates based on chemoattractant
        arr = trail map array
        '''
        L, C, R = self.get_sensor_values(arr)

        if ((C > L) and (C > R)):  # Center > both: stay facing same direction, do nothing
            self.phi += 0
            self.update_sensors()
        elif ((L == R) and C < L):  # L, R are equal, center is less - randomly rotate L/R
            rn = np.random.randint(2)
            if rn == 0:
                self.phi += self.RA
                self.update_sensors()
            else:
                self.phi -= self.RA
                self.update_sensors()
        elif (R > L):
            self.phi += self.RA
            self.update_sensors()
        elif (L > R):
            self.phi -= self.RA
            self.update_sensors()
        else:  # all three are the same - stay facing same direction
            self.phi += 0
            self.update_sensors()


def scheduler(N=200, M=200, pp=0.07, sigma=0.65, const=0.85,
              SO=9, SA=np.pi / 8, RA=np.pi / 4, steps=500,
              intervals=8, plot=False, animate=True):
    '''
    generates the environment (NxM) with pp% of environment populated
    particles: Sensor Offset, Sensor Angle, Rotation Angle
    chemoattractant: constant multiplier, sigma (gaussian filter)
    evolve simulation for 500 steps, grab plots at specific intervals
    choice to plot intervals OR animate the desired simulation
    '''
    Env = Environment(N, M, pp)
    Env.populate(SA, RA, SO)

    if (plot == True):
        dt = int(steps / intervals)
        samples = np.linspace(0, dt * intervals, intervals + 1)  # integer samples
        for i in range(steps):
            Env.diffusion_operator(const, sigma)
            Env.motor_stage()
            Env.sensory_stage()
            if i in samples:
                fig = plt.figure(figsize=(8, 8), dpi=200);
                ax1 = fig.add_subplot(111);
                ax1.imshow(Env.trail_map);
                ax1.set_title('Chemoattractant Map, step={}'.format(i));
                # display some information about parameters used
                ax1.text(0, -10,
                         'SA: {:.2f}  SO: {}  RA: {:.2f}  pop: {:.0f}%'.format(np.degrees(SA), SO, np.degrees(RA),
                                                                               pp * 100));  # hard code -10, since most likely using big grid
                plt.savefig('sim_t{}.png'.format(i));
                plt.clf();

    elif (animate == True):
        # this can take a while for large environments, high population
        # also generates very large .gif files, play with values to get smaller files
        ims = []
        fig = plt.figure(figsize=(8, 8), dpi=100);
        ax = fig.add_subplot(111);
        for i in range(steps):
            Env.diffusion_operator(const, sigma)
            Env.motor_stage()
            Env.sensory_stage()
            txt = plt.text(0, -10,
                           'iteration: {}    SA: {:.2f}    SO: {}    RA: {:.2f}    %pop: {}%'.format(i, np.degrees(SA),
                                                                                                     SO, np.degrees(RA),
                                                                                                     pp * 100));
            im = plt.imshow(Env.trail_map, animated=True);
            ims.append([im, txt])
        fig.suptitle('Powerplant Blob Linking');
        ani = animation.ArtistAnimation(fig, ims, interval=50, blit=True, repeat_delay=1000);
        ani.save('blob.mp4');


def main():
    '''
    runs the scheduler as is, with default parameters except lower step size
    generates 8 plots in the directory at different time intervals.
    '''
    scheduler(steps=2000)
    return 0


if __name__ == "__main__":
    main()


                </code></pre>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="bg-indigo-600">
        <div class="mx-auto max-w-7xl py-16 px-4 sm:py-24 sm:px-6 lg:px-8">
          <h2 class="text-center text-base font-semibold text-gray-200">Ils nous font confiance.</h2>
          <div class="mt-8 grid grid-cols-2 gap-8 md:grid-cols-6 lg:grid-cols-5">
            <div class="col-span-1 flex justify-center md:col-span-2 lg:col-span-1">
              <img class="h-12" src="https://tailwindui.com/img/logos/tuple-logo-gray-400.svg" alt="Tuple">
            </div>
            <div class="col-span-1 flex justify-center md:col-span-2 lg:col-span-1">
              <img class="h-12" src="https://tailwindui.com/img/logos/mirage-logo-gray-400.svg" alt="Mirage">
            </div>
            <div class="col-span-1 flex justify-center md:col-span-2 lg:col-span-1">
              <img class="h-12" src="https://tailwindui.com/img/logos/statickit-logo-gray-400.svg" alt="StaticKit">
            </div>
            <div class="col-span-1 flex justify-center md:col-span-3 lg:col-span-1">
              <img class="h-12" src="https://tailwindui.com/img/logos/transistor-logo-gray-400.svg" alt="Transistor">
            </div>
            <div class="col-span-2 flex justify-center md:col-span-3 lg:col-span-1">
              <img class="h-12" src="https://tailwindui.com/img/logos/workcation-logo-gray-400.svg" alt="Workcation">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import Prism from "prismjs";
import "../static/prism-python.min.js"
import "prismjs/themes/prism.css";

export default {
  name: 'home',
  components: {},
  computed:{},
  mounted() {
    window.Prism = window.Prism || {};
    window.Prism.manual = true;
    Prism.highlightAll(); // highlight your code on mount
  }
}
</script>

<style>
pre, code {
  @apply text-sm m-0 rounded-r-xl h-[500px] overflow-scroll !important;
}
</style>
