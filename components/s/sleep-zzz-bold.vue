<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck5zovrth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ck5zovrth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:sleep-zzz-bold" /></template>
