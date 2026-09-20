<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww3qszowu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww3qszowu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:masq" /></template>
