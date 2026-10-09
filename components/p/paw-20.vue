<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjpr8ebst.css';
import '../../css/f/f_bvfu90l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cjpr8ebst"/><path class="f_bvfu90l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paw-20" /></template>
