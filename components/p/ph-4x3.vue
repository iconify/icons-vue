<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z748_ebdy.css';
import '../../css/e/e7vpmh2zb.css';
import '../../css/z/zsw4udyjx.css';
import '../../css/z/zvp_pt6pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="z748_ebdy"/><path class="e7vpmh2zb"/><path class="zsw4udyjx"/><path class="zvp_pt6pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ph-4x3" /></template>
