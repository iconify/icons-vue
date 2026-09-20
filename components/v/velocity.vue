<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exaqg9f9e.css';
import '../../css/j/joioafbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path paint-order="fill markers stroke" class="exaqg9f9e"/><path class="joioafbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:velocity" /></template>
