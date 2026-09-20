<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k81cr0bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:map-search-sharp" /></template>
<style>
.k81cr0bgd {
  fill: currentColor;
  d: path("M17.528 17.567q.659-.644.664-1.663q.006-.985-.658-1.646q-.665-.662-1.65-.662t-1.645.662t-.662 1.646t.662 1.646t1.645.662t1.644-.645m-1.643 1.645q-1.362 0-2.335-.973t-.973-2.335t.973-2.335t2.335-.973t2.334.973t.973 2.335q0 .556-.166 1.049t-.48.905L21 20.292l-.688.708l-2.454-2.454q-.412.333-.905.5q-.493.165-1.068.165M4 19.765V5.78l5-1.704l6 2.1l5-1.94v7.765q-.817-.871-1.88-1.33t-2.236-.46q-.346 0-.692.049t-.692.128V7.004l-5-1.746V17.64z");
}

</style>
