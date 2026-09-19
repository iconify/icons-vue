<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py--2fjvj.css';
import '../../css/n/nthaozbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":24};
const content = `<path class="py--2fjvj"/><path class="nthaozbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:netflix" /></template>
