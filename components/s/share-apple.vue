<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbgvppbqc.css';
import '../../css/w/w1c22wekr.css';
import '../../css/l/l8y7zreew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="bbgvppbqc"/><path class="w1c22wekr"/><path class="l8y7zreew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:share-apple" /></template>
