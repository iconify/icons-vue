<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq3da4h7l.css';
import '../../css/s/slygv4qud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq3da4h7l"/><path class="slygv4qud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:trash-24" /></template>
