<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1dt1gbdl.css';
import '../../css/r/r6mz58bje.css';
import '../../css/z/z08a_ruyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t1dt1gbdl"/><path class="r6mz58bje"/><path class="z08a_ruyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tv-outline" /></template>
