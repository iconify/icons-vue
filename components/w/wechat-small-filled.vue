<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfae7sbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mfae7sbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:wechat-small-filled" /></template>
