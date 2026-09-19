<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkgfbqhls.css';
import '../../css/w/wckr9kb1z.css';
import '../../css/q/q285h9bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="zkgfbqhls"/><path class="wckr9kb1z"/><path class="q285h9bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:universal-access" /></template>
