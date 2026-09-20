<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox2enz3rd.css';
import '../../css/g/gycyi0r7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox2enz3rd"/><path class="gycyi0r7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sliders-24" /></template>
