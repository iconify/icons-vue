<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n61vkeq-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n61vkeq-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:upload-06" /></template>
