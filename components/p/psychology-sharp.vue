<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soxznrbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:psychology-sharp" /></template>
<style>
.soxznrbjo {
  fill: currentColor;
  d: path("M11.442 14.577h1.116l.073-.923q.392-.075.747-.262q.355-.186.595-.484l.804.404l.558-.95l-.731-.539q.165-.411.165-.823t-.165-.823l.73-.538l-.557-.95l-.804.403q-.24-.298-.595-.484q-.355-.187-.747-.262l-.073-.923h-1.116l-.073.923q-.392.075-.747.262q-.355.186-.595.484l-.804-.403l-.557.95l.73.538q-.165.412-.165.823t.165.823l-.73.539l.557.95l.804-.404q.24.298.595.484q.355.187.747.262zm-.764-2.255q-.543-.543-.543-1.322t.543-1.322T12 9.135t1.322.543q.544.543.544 1.322t-.544 1.322q-.543.544-1.322.544t-1.322-.544M7 21v-3.762q-1.425-1.3-2.212-2.922T4 10.981q0-3.327 2.337-5.654Q8.673 3 12 3q2.702 0 4.884 1.645t2.83 4.25L20.987 14H18v5h-4v2z");
}

</style>
