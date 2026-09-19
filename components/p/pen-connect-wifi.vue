<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufy6p9byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufy6p9byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pen-connect-wifi" /></template>
