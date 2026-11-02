<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn4hjabqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn4hjabqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:webhook-2-fill" /></template>
