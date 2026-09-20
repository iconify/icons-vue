<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdvkxgexj.css';
import '../../css/l/lez75epbo.css';
import '../../css/c/c1cb-s12j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdvkxgexj"/><path class="lez75epbo"/><path class="c1cb-s12j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mnst" /></template>
