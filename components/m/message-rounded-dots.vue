<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uswo5nbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uswo5nbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-rounded-dots" /></template>
