<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnqx-61mq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15.98,"height":18.229,"left":-1.663,"top":-1.663};
const content = `<path class="rnqx-61mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pokerstars" /></template>
