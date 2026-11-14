<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvy1vj65t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:slash-forward" /></template>
<style>
.gvy1vj65t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m17.178 2.821l-9 19q-.032.067-.076.126t-.099.109t-.118.088t-.133.062t-.142.036q-.073.011-.147.007t-.146-.022q-.071-.018-.138-.049q-.135-.064-.235-.175t-.15-.251t-.043-.289t.071-.284l9-19q.064-.135.175-.235t.251-.15t.289-.043t.284.071q.067.032.126.076t.109.099t.088.118q.037.063.062.133q.025.069.036.142t.007.147t-.022.146t-.049.138");
}

</style>
