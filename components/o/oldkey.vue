<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewxyoiu2q.css';
import '../../css/z/zc4hgcctu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ewxyoiu2q"/><path class="zc4hgcctu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:oldkey" /></template>
