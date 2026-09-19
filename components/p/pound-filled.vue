<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd8hrac-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd8hrac-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pound-filled" /></template>
