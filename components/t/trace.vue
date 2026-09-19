<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7sr6ubzr.css';
import '../../css/b/bxwa93b2u.css';
import '../../css/e/ec1xl5bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7sr6ubzr"/><path class="bxwa93b2u"/><path class="ec1xl5bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:trace" /></template>
