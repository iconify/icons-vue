<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kegfed51p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kegfed51p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-alt-dots" /></template>
