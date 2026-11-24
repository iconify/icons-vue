<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wssuxnb5s.css';
import '../../css/h/h4-_8v1va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wssuxnb5s"/><path clip-rule="evenodd" class="h4-_8v1va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-cog-filled" /></template>
