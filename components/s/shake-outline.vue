<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoz0_bc9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="aoz0_bc9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:shake-outline" /></template>
