<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu5flgbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu5flgbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:package-search" /></template>
