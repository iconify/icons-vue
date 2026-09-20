<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4o-mf99w.css';
import '../../css/c/cnzpvyp0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4o-mf99w"/><path clip-rule="evenodd" class="cnzpvyp0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:recive-twice-square-outline" /></template>
