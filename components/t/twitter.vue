<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxn_06esw.css';
import '../../css/z/zq5w5wbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="lxn_06esw"/><path class="zq5w5wbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:twitter" /></template>
