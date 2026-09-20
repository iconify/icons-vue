<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhp_tvhii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhp_tvhii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wechat-channels-fill" /></template>
