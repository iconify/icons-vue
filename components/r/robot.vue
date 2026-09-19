<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r00p3nbjo.css';
import '../../css/r/r0cgx2bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r00p3nbjo"/><path class="r0cgx2bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:robot" /></template>
