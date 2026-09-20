<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc5znpb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc5znpb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:user-exclamation" /></template>
