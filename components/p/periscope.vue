<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gac6sofbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":19,"height":24};
const content = `<path class="gac6sofbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:periscope" /></template>
