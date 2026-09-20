<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsa_8obst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsa_8obst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skateboard" /></template>
