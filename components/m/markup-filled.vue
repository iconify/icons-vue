<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbwx9qiay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbwx9qiay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:markup-filled" /></template>
