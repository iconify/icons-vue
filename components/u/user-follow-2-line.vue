<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dih28hbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dih28hbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-follow-2-line" /></template>
