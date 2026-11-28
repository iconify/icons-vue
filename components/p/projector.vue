<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfnndy6yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfnndy6yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:projector" /></template>
