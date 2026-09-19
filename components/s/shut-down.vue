<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gec1cwtah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gec1cwtah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shut-down" /></template>
