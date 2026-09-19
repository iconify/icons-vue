<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0ufzdh3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0ufzdh3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:pipe-3d" /></template>
