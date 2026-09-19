<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vulxtnpzy.css';
import '../../css/d/dd6c-mb8w.css';
import '../../css/t/tzalp-b_a.css';
import '../../css/z/z1yhh2-zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vulxtnpzy"/><path class="dd6c-mb8w"/><path class="tzalp-b_a"/><path class="z1yhh2-zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pike" /></template>
