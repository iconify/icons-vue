<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y051qnbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y051qnbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:map-filled" /></template>
