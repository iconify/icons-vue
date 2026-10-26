<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-ygnwx-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-ygnwx-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:seafile" /></template>
