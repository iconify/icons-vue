<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlo2z0biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlo2z0biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-down-bold" /></template>
