<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzc_g-bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzc_g-bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nicehash" /></template>
