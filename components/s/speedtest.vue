<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gse48h3rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gse48h3rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:speedtest" /></template>
