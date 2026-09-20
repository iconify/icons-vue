<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulyx1nwsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulyx1nwsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:shikimori" /></template>
