<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjpzg3o6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjpzg3o6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-4-fill" /></template>
