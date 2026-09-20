<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqe5zm-hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqe5zm-hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:vip-crown-fill" /></template>
