<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cis9tc4cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cis9tc4cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pyr" /></template>
