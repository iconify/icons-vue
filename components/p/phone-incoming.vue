<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkbp6n8mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkbp6n8mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:phone-incoming" /></template>
