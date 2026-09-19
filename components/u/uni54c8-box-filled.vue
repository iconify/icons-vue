<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdqkzx6-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xdqkzx6-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni54c8-box-filled" /></template>
