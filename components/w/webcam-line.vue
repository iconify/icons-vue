<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo07-2dhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo07-2dhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:webcam-line" /></template>
