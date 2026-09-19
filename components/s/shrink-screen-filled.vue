<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uev-y9bxq.css';
import '../../css/h/hurcj9b3v.css';
import '../../css/v/v758r-tyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="uev-y9bxq"/><path class="hurcj9b3v"/><path class="v758r-tyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:shrink-screen-filled" /></template>
