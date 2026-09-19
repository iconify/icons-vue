<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im6fgsjxz.css';
import '../../css/x/xwibx1gek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im6fgsjxz"/><path class="xwibx1gek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:widget-small" /></template>
