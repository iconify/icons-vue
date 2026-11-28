<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kslcz4beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kslcz4beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-circle-solid" /></template>
