<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcl2e-hth.css';
import '../../css/d/dnt6pzbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcl2e-hth"/><path class="dnt6pzbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-rotate-cw-filled" /></template>
