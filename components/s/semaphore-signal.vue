<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf-ei04hx.css';
import '../../css/f/faw3i3g2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="lf-ei04hx"/><path class="faw3i3g2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:semaphore-signal" /></template>
