<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjn3wobdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjn3wobdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:music-search" /></template>
