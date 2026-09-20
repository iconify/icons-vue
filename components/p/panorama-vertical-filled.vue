<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh4nc23vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh4nc23vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:panorama-vertical-filled" /></template>
