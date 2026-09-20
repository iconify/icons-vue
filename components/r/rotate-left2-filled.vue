<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q75n7ib4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q75n7ib4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:rotate-left2-filled" /></template>
