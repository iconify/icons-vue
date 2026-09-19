<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5ieuchfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s5ieuchfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:user-delete" /></template>
