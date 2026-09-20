<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxbyoqb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxbyoqb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:main-component-filled" /></template>
