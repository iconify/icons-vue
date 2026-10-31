<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqe71b-9z.css';
import '../../css/l/l1kbw1b1l.css';
import '../../css/c/cfoaekbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="rqe71b-9z"/><path class="l1kbw1b1l"/><path class="cfoaekbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:norway" /></template>
