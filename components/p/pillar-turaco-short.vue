<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnn050b4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnn050b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pillar-turaco-short" /></template>
