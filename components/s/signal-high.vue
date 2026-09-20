<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qah5gg87y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qah5gg87y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:signal-high" /></template>
