<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1wy29y8k.css';
import '../../css/h/hhrsgwhff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1wy29y8k"/><path class="hhrsgwhff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pharmacy" /></template>
