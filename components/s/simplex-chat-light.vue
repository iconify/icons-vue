<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrb6tcbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zrb6tcbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:simplex-chat-light" /></template>
