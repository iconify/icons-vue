<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3qg2sb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3qg2sb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:message-circle-dashed" /></template>
