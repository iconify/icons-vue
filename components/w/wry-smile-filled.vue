<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a90emgbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a90emgbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:wry-smile-filled" /></template>
