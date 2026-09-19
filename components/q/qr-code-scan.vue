<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/typ1igblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="typ1igblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:qr-code-scan" /></template>
