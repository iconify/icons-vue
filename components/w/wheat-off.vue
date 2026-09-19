<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2je2ob9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2je2ob9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wheat-off" /></template>
