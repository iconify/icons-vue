<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss-qr7p6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ss-qr7p6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:mobile-fill" /></template>
