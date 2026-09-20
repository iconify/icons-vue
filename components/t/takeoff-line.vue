<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwxp84b-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwxp84b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:takeoff-line" /></template>
