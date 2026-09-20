<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4uu2r1iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:map-search-outline" /></template>
<style>
.j4uu2r1iq {
  fill: currentColor;
  d: path("M15.5 10.23v-.038zV7.005zM5.042 19.355q-.384.142-.713-.084T4 18.634V6.404q0-.268.13-.489t.378-.307L9 4.077l6 2.1l3.958-1.53q.384-.143.713.054t.329.588v6.713q-.221-.248-.464-.463T19 11.146V5.7l-3.5 1.304v3.227q-.275.019-.516.049q-.24.03-.484.109V7.004l-5-1.746V17.64zM5 18.3l3.5-1.342v-11.7L5 6.45zm12.528-.733q.659-.644.664-1.663q.006-.985-.658-1.646q-.665-.662-1.65-.662t-1.646.662t-.661 1.646t.661 1.646t1.646.662t1.644-.645m-1.643 1.645q-1.362 0-2.335-.973t-.973-2.335t.973-2.335t2.334-.973t2.335.973t.973 2.335q0 .556-.166 1.049q-.167.493-.48.905L21 20.292l-.688.708l-2.454-2.454q-.412.333-.905.5q-.493.165-1.068.165M8.5 5.259v11.7z");
}

</style>
