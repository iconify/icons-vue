<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iclr56bfn.css';
import '../../css/w/wdgf1rbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iclr56bfn"/><path class="wdgf1rbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:stop-24" /></template>
