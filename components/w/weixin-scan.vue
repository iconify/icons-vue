<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao01rhb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ao01rhb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:weixin-scan" /></template>
