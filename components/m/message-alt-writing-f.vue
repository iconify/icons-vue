<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o812x4bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="o812x4bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:message-alt-writing-f" /></template>
