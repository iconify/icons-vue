<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q36m0bb5w.css';
import '../../css/x/x84itwbxe.css';
import '../../css/o/otwfeac8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="q36m0bb5w"/><path class="x84itwbxe"/><path class="otwfeac8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:tape-drive-line" /></template>
