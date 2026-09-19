<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf-wdxbtk.css';
import '../../css/k/krz3t3bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf-wdxbtk"/><path class="krz3t3bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:remove" /></template>
