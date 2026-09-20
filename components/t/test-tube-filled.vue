<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqfftaccz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rqfftaccz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:test-tube-filled" /></template>
