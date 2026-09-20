<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey1o4hbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey1o4hbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:microsoft" /></template>
