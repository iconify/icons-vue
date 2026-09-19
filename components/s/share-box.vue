<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zern9db0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zern9db0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:share-box" /></template>
