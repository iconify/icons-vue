<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0omkob4z.css';
import '../../css/q/qx5t5kjwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m0omkob4z"/><path class="qx5t5kjwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:zsh-wordmark" /></template>
