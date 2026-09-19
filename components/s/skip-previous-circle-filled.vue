<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd_e_9btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd_e_9btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:skip-previous-circle-filled" /></template>
