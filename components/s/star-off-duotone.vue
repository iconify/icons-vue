<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcvs5vdpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcvs5vdpy primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:star-off-duotone" /></template>
