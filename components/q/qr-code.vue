<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkizyy9_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkizyy9_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:qr-code" /></template>
