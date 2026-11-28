<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb60x0cdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb60x0cdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tulip-heart" /></template>
