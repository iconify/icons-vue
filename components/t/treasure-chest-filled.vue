<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq91mq-sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq91mq-sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:treasure-chest-filled" /></template>
