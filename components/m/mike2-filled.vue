<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1vrrv3og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1vrrv3og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:mike2-filled" /></template>
