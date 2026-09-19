<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj59ymb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj59ymb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pin-slash-alt-filled" /></template>
