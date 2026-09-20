<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqusm6bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqusm6bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:transfer-v-filled" /></template>
