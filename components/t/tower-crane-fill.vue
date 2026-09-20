<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec6h5ubjk.css';
import '../../css/c/cyglm8gxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ec6h5ubjk"/><path class="cyglm8gxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tower-crane-fill" /></template>
