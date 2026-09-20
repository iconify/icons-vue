<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wix3a056v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wix3a056v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:twitter-old" /></template>
