<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuh_jbm9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuh_jbm9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:message-rounded" /></template>
