<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enm4i5bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="enm4i5bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pin-pad-with-peso" /></template>
