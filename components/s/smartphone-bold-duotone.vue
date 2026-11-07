<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4udjm4ma.css';
import '../../css/p/pzq_i-bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4udjm4ma"/><path class="pzq_i-bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-bold-duotone" /></template>
