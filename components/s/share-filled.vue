<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrnkw556h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrnkw556h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:share-filled" /></template>
