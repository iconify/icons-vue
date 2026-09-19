<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nln80aciw.css';
import '../../css/k/k01r6evgn.css';
import '../../css/k/kk0hmeb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nln80aciw"/><path class="k01r6evgn"/><path class="kk0hmeb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sustainability" /></template>
