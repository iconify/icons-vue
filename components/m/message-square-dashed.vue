<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpbws8lvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpbws8lvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:message-square-dashed" /></template>
