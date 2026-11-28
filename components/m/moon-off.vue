<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj1yuh1cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj1yuh1cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:moon-off" /></template>
