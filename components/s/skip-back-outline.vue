<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkb-0tb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkb-0tb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:skip-back-outline" /></template>
