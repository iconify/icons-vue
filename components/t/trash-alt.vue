<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfrikpbvv.css';
import '../../css/e/etxysdbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfrikpbvv"/><path class="etxysdbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:trash-alt" /></template>
