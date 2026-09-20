<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcyumdbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:whatshot-outline-sharp" /></template>
<style>
.wcyumdbrj {
  fill: currentColor;
  d: path("M12 22q-1.65 0-3.187-.513T6 20l1.45-1.45q1.05.725 2.2 1.088T12 20q3.325 0 5.663-2.337T20 12t-2.337-5.663T12 4T6.337 6.338T4 12H2q0-2.075.788-3.9t2.137-3.175T8.1 2.788T12 2t3.888.788t3.174 2.15t2.15 3.175t.788 3.875t-.787 3.887t-2.15 3.188t-3.175 2.15T12 22m-8.025-4.075L8.05 13.85l3 2.5L16 11.4V14h2V8h-6v2h2.6l-3.65 3.65l-3-2.5l-5.025 5.025q.275.575.488.938t.562.812M12 12");
}

</style>
