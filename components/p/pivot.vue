<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfiq-bc6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfiq-bc6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pivot" /></template>
