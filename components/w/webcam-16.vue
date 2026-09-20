<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg2fhkbcg.css';
import '../../css/l/l-5p0fbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mg2fhkbcg"/><path clip-rule="evenodd" class="l-5p0fbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:webcam-16" /></template>
