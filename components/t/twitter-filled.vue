<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geksnn.css';
import '../../css/s/so-from-62.css';
import '../../css/f/fill-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geksnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:twitter-filled" /></template>
