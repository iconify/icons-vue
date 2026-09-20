<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs2okpbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs2okpbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:moonbeam" /></template>
