<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np1z57bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="np1z57bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:open-a-i-filled" /></template>
