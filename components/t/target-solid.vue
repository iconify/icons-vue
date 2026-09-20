<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0yw49byf.css';
import '../../css/u/u-9mz-bzz.css';
import '../../css/f/fydwzq94k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f0yw49byf"/><path clip-rule="evenodd" class="u-9mz-bzz"/><path clip-rule="evenodd" class="fydwzq94k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:target-solid" /></template>
