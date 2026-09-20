<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3amo-b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3amo-b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:skip-forward" /></template>
