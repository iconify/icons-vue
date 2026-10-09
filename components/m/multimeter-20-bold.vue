<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4enznbyj.css';
import '../../css/k/kjieaf7cx.css';
import '../../css/p/pvg5xqbkw.css';
import '../../css/y/y99owegkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x4enznbyj"/><path class="kjieaf7cx"/><path class="pvg5xqbkw"/><path class="y99owegkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:multimeter-20-bold" /></template>
