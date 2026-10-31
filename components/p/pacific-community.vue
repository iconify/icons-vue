<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr80jrxoc.css';
import '../../css/c/c_321cctz.css';
import '../../css/e/eo8l1gwux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="lr80jrxoc"/><path class="c_321cctz"/><path class="eo8l1gwux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:pacific-community" /></template>
