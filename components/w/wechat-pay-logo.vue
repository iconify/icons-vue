<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5q-9mbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5q-9mbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:wechat-pay-logo" /></template>
