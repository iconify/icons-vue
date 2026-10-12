<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx95jbbja.css';
import '../../css/x/xcxa9bb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kx95jbbja"/><path class="xcxa9bb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:rocket-fill-20" /></template>
