<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az1a-kbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az1a-kbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:map-pin-plus" /></template>
