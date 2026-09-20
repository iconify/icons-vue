<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx1wr_bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx1wr_bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:volume" /></template>
