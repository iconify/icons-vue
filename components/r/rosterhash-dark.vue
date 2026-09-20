<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewgzu34ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ewgzu34ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rosterhash-dark" /></template>
