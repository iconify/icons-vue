<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0wqm8b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0wqm8b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:message-dots" /></template>
