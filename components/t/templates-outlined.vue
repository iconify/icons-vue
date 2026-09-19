<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdypsia2b.css';
import '../../css/h/hztfv9bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdypsia2b"/><path class="hztfv9bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:templates-outlined" /></template>
