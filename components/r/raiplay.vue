<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfsw7b0sv.css';
import '../../css/a/alo1w6bul.css';
import '../../css/s/s2jd-4bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfsw7b0sv"/><path class="alo1w6bul"/><path class="s2jd-4bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:raiplay" /></template>
