<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzac1ibbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzac1ibbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:zap" /></template>
