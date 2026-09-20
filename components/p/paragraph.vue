<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz0-u9bdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz0-u9bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:paragraph" /></template>
