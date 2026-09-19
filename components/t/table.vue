<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpeh4lb3t.css';
import '../../css/p/pan8axb2r.css';
import '../../css/k/kfb89rzgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="fpeh4lb3t"/><path class="pan8axb2r"/><path class="kfb89rzgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:table" /></template>
