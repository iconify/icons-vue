<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqq4c7qxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqq4c7qxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:transmission-bt" /></template>
