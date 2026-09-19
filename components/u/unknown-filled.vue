<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jre_-vbgm.css';
import '../../css/v/v_ia24bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jre_-vbgm"/><path class="v_ia24bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:unknown-filled" /></template>
