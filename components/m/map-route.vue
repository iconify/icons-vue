<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iknee7b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iknee7b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-route" /></template>
