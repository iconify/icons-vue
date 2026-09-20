<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jajm5-bsz.css';
import '../../css/k/k_heijbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jajm5-bsz"/><path class="k_heijbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sticker-fill" /></template>
