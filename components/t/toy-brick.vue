<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e53o5ubcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e53o5ubcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:toy-brick" /></template>
