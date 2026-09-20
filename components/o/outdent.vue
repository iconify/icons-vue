<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0lgx_3bc.css';
import '../../css/d/dh1xuibar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="c0lgx_3bc"/><path clip-rule="evenodd" class="dh1xuibar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:outdent" /></template>
