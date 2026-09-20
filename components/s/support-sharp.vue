<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy4t45age"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:support-sharp" /></template>
<style>
.qy4t45age {
  fill: currentColor;
  d: path("M8.494 20.29q-1.642-.711-2.858-1.926q-1.215-1.216-1.926-2.858T3 12t.71-3.506q.711-1.642 1.927-2.857Q6.852 4.42 8.494 3.71T12 3t3.506.71q1.642.711 2.857 1.927q1.216 1.215 1.926 2.857Q21 10.137 21 12t-.71 3.506q-.711 1.642-1.926 2.857q-1.216 1.216-2.858 1.926Q13.864 21 12 21t-3.506-.71m.606-.84l1.739-3.942q-.82-.28-1.419-.884T8.53 13.2l-4.018 1.65q.594 1.6 1.794 2.8t2.794 1.8m-.57-8.65q.253-.82.861-1.395Q10 8.829 10.8 8.53L9.15 4.51q-1.62.62-2.82 1.82T4.513 9.15zm5.374 3.104q.788-.788.788-1.904t-.788-1.904T12 9.308t-1.904.788T9.308 12t.788 1.904t1.904.788t1.904-.788m.996 5.546q1.575-.6 2.763-1.787T19.45 14.9l-3.942-1.739q-.26.8-.862 1.4t-1.396.908zm.57-8.7l3.98-1.65q-.6-1.575-1.787-2.762T14.9 4.55l-1.65 3.992q.756.317 1.333.878t.886 1.33");
}

</style>
