<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld1e0bb3t.css';
import '../../css/f/frzki349x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld1e0bb3t"/><path clip-rule="evenodd" class="frzki349x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:print-fill" /></template>
