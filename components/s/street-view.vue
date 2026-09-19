<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnce0pb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnce0pb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:street-view" /></template>
