<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwqhfdsoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwqhfdsoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:type-text-solid" /></template>
