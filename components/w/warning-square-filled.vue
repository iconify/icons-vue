<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg817wbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kg817wbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:warning-square-filled" /></template>
