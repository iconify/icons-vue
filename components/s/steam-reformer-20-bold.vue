<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7ggesbml.css';
import '../../css/b/by_x3ac6t.css';
import '../../css/s/saqzqrcve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n7ggesbml"/><path class="by_x3ac6t"/><path class="saqzqrcve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:steam-reformer-20-bold" /></template>
