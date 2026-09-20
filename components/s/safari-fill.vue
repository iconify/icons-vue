<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdsyej-ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdsyej-ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safari-fill" /></template>
