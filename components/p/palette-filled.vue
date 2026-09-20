<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfs826bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfs826bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:palette-filled" /></template>
