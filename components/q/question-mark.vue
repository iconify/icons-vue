<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wta6cob2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wta6cob2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:question-mark" /></template>
