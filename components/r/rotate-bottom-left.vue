<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn9r8cc9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn9r8cc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-bottom-left" /></template>
