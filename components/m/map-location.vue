<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uryce_auj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uryce_auj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:map-location" /></template>
