<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxmp_-hzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lxmp_-hzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roman-numeral-vii" /></template>
