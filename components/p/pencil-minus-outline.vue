<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvo6zwbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvo6zwbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pencil-minus-outline" /></template>
