<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf86qebjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf86qebjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rows-2-bold" /></template>
