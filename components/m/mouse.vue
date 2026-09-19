<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa7gedctx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oa7gedctx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:mouse" /></template>
