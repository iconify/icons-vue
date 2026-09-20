<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_z3mvb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_z3mvb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pyload-dark" /></template>
