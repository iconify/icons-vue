<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aea866bch.css';
import '../../css/v/vbj9b3b9v.css';
import '../../css/k/kmkesyb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aea866bch"/><path class="vbj9b3b9v"/><path class="kmkesyb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:pisces" /></template>
