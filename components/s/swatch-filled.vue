<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt7zdbbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt7zdbbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:swatch-filled" /></template>
