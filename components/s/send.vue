<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o966jfvtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o966jfvtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:send" /></template>
