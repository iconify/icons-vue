<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrr2rz3sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrr2rz3sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-fill" /></template>
