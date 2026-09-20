<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul6u5tqnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:support-agent-outline-sharp" /></template>
<style>
.ul6u5tqnd {
  fill: currentColor;
  d: path("M11.77 20v-1H19v-7.446q0-2.81-2.066-4.693Q14.867 4.977 12 4.977T7.066 6.861T5 11.554v5.696H3v-4.706h1l.017-1.229q.046-1.565.709-2.9T6.47 6.092t2.514-1.54T12 4t3.014.552q1.428.552 2.513 1.538q1.085.985 1.744 2.32q.66 1.334.712 2.9L20 12.544h1v4.706h-1V20zm-2.925-6.672q-.23-.21-.23-.52t.23-.53t.54-.22t.539.22t.23.53t-.23.52t-.54.21t-.539-.21m5.231 0q-.23-.21-.23-.52t.23-.53t.54-.22t.539.22t.23.53t-.23.52t-.54.21t-.539-.21M6.717 11.95q-.136-2.246 1.447-3.829q1.582-1.583 3.886-1.583q1.936 0 3.432 1.163t1.826 3.055q-1.987-.025-3.688-1.014t-2.61-2.75q-.362 1.731-1.505 3.034q-1.144 1.303-2.788 1.924");
}

</style>
