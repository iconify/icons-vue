<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw5pvbc7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1728};
const content = `<path class="cw5pvbc7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:wechat" /></template>
