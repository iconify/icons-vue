<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwtxp2blp.css';
import '../../css/k/kkn84ffqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="pwtxp2blp"/><path class="kkn84ffqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:right-arrow-curving-up" /></template>
