<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni-2a0bqi.css';
import '../../css/l/l78r7fgdc.css';
import '../../css/f/f39hclbhm.css';
import '../../css/o/opcti8bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni-2a0bqi"/><path class="l78r7fgdc"/><path class="f39hclbhm"/><path class="opcti8bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:repeat" /></template>
