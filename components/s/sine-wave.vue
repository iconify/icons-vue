<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0qad_bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0qad_bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:sine-wave" /></template>
