<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s46z6zm0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s46z6zm0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:water-bottle-solid" /></template>
