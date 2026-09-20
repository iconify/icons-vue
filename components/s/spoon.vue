<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt9f0cb0i.css';
import '../../css/b/brrdf9bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="lt9f0cb0i"/><path class="brrdf9bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:spoon" /></template>
