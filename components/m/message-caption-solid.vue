<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc3gvlbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yc3gvlbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:message-caption-solid" /></template>
