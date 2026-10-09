<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz30y8b3r.css';
import '../../css/g/gtn82neio.css';
import '../../css/e/e3lx9cbyl.css';
import '../../css/j/jgfshtvfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dz30y8b3r"/><path class="gtn82neio"/><path class="e3lx9cbyl"/><path class="jgfshtvfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-home-20" /></template>
