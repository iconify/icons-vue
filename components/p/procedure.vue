<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_6pa4b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:procedure" /></template>
<style>
.d_6pa4b7u {
  fill: currentColor;
  d: path("M18.27 10.73q-.74 0-1.622-.46t-1.673-1.276t-1.251-1.698t-.46-1.634q0-.233.048-.4t.144-.264q.535-.534 2.234-.907q1.699-.372 3.545-.354q.298.011.489.063q.192.052.295.156q.098.098.153.278t.066.46q.03 1.86-.32 3.56t-.891 2.24q-.115.116-.31.176q-.196.06-.448.06m.51-2.326q.223-.681.335-1.594q.111-.914.155-2.08q-.98-.024-1.897.1q-.916.124-1.685.366q.544.296.999.627q.455.33.833.71q.423.423.742.884t.518.987m-.51 1.327q-.148-.615-.528-1.295q-.381-.68-.935-1.228q-.567-.567-1.232-.945t-1.28-.532q.05.575.435 1.29t.954 1.285q.6.6 1.303.987q.703.388 1.283.438m3.031 8.257L16.812 13.5h-10l-4.8-4.8l.688-.688L7.189 12.5h10l4.8 4.8zM8.5 20.981v-3.385q0-.671.472-1.143t1.144-.472h3.768q.672 0 1.144.472t.472 1.143v3.385z");
}

</style>
