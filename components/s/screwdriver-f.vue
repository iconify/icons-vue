<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zym811ndz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1,"top":-1};
const content = `<path class="zym811ndz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:screwdriver-f" /></template>
