<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi8bn8bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi8bn8bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:solid" /></template>
