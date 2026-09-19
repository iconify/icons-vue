<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxlo3ac_e.css';
import '../../css/x/xt4ay30jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="kxlo3ac_e"/><path class="xt4ay30jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:up" /></template>
