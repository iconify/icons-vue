<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7nezibak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7nezibak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:window-filled" /></template>
