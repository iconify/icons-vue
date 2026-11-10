<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpx07wtst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpx07wtst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:user-check" /></template>
