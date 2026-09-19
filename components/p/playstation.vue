<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imxv1m5kb.css';
import '../../css/t/t8iobcbuq.css';
import '../../css/l/l0krix3kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="imxv1m5kb"/><path class="t8iobcbuq"/><path class="l0krix3kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:playstation" /></template>
