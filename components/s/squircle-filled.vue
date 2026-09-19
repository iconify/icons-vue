<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5eh_3-2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5eh_3-2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:squircle-filled" /></template>
