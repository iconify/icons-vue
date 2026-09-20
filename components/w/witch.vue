<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qho7iu1hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qho7iu1hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:witch" /></template>
