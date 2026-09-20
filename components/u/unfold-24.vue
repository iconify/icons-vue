<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnghg2bjh.css';
import '../../css/f/f7ef8jq2f.css';
import '../../css/x/xtctq8bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnghg2bjh"/><path class="f7ef8jq2f"/><path class="xtctq8bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:unfold-24" /></template>
