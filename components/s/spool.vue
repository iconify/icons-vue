<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca7cey2zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca7cey2zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:spool" /></template>
