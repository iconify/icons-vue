<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f770scbge.css';
import '../../css/b/bgy0nnrsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f770scbge"/><path class="bgy0nnrsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:social-rewards-like-bubble" /></template>
