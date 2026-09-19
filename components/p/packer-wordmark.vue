<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chs_wwive.css';
import '../../css/d/d4xm7xbec.css';
import '../../css/z/z1hhkczws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="chs_wwive"/><path class="d4xm7xbec"/><path class="z1hhkczws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:packer-wordmark" /></template>
