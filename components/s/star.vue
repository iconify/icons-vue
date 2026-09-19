<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcu_p7b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcu_p7b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:star" /></template>
