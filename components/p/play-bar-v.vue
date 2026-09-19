<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlrmq-b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlrmq-b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:play-bar-v" /></template>
