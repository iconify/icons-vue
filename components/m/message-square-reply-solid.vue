<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsygm4b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsygm4b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-reply-solid" /></template>
