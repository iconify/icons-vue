<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg28_o4co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg28_o4co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:user-check" /></template>
