<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxcuk3bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxcuk3bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rectangle-fill" /></template>
