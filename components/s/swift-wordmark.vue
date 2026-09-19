<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce4x6tx7w.css';
import '../../css/w/w0za-obmf.css';
import '../../css/t/tgr0ac0hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ce4x6tx7w"/><path class="w0za-obmf"/><path class="tgr0ac0hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:swift-wordmark" /></template>
