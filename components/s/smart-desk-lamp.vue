<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7o3g-5yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7o3g-5yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:smart-desk-lamp" /></template>
