<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tni30y4jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tni30y4jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:reading-filled" /></template>
