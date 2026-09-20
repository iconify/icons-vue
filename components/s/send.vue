<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lai0ygbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lai0ygbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:send" /></template>
