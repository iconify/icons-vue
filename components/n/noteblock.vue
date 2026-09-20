<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vev8xfbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vev8xfbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:noteblock" /></template>
