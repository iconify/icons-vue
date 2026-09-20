<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsb8z6dli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsb8z6dli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:notification-error-filled" /></template>
