<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3-zj-h9b.css';
import '../../css/s/sbjtnhxpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3-zj-h9b"/><path class="sbjtnhxpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:play-circle" /></template>
