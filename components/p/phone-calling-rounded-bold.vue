<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cquf3bccv.css';
import '../../css/q/qv0degibz.css';
import '../../css/j/jcweppbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cquf3bccv"/><path class="qv0degibz"/><path class="jcweppbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:phone-calling-rounded-bold" /></template>
