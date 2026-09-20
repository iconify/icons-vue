<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smpy58bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smpy58bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:new-japan-pro-wrestling" /></template>
