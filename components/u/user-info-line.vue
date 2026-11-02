<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbk25gbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbk25gbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-info-line" /></template>
