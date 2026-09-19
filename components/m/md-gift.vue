<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bit1shupq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bit1shupq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-gift" /></template>
