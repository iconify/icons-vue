<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeh6a5f4t.css';
import '../../css/a/anpcbdbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yeh6a5f4t"/><path class="anpcbdbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:warningsign" /></template>
