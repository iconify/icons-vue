<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uno_xbqqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uno_xbqqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pear-filled" /></template>
