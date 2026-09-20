<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tszwngbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tszwngbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vc" /></template>
