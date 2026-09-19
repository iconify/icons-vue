<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do2adqbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do2adqbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:object-ungroup" /></template>
