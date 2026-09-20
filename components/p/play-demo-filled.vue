<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8l-zzb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8l-zzb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:play-demo-filled" /></template>
