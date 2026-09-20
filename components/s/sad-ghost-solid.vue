<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqfe0qbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqfe0qbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:sad-ghost-solid" /></template>
