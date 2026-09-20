<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxqd5xezl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxqd5xezl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:remark" /></template>
