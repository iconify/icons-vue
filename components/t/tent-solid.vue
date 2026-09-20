<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi7s_kbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi7s_kbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tent-solid" /></template>
