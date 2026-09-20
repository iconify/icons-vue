<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckgm-9y5r.css';
import '../../css/v/v_xa8ibqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ckgm-9y5r"/><path class="v_xa8ibqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:programming-code-idea" /></template>
