<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln87rknis.css';
import '../../css/c/ceswd_37u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ln87rknis"/><path class="ceswd_37u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:wave" /></template>
