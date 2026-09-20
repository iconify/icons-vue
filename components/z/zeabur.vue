<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2027-biw.css';
import '../../css/l/lgeglqbcu.css';
import '../../css/z/zy6utib6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p2027-biw"/><path class="lgeglqbcu"/><path class="zy6utib6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:zeabur" /></template>
