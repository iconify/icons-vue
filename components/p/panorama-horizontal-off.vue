<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x40gnkblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x40gnkblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:panorama-horizontal-off" /></template>
