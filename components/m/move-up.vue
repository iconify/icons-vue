<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1-kk3b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1-kk3b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:move-up" /></template>
