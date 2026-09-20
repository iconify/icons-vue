<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0_z0tvmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0_z0tvmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:thumbs-up" /></template>
