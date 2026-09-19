<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q55yeab0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q55yeab0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:smallbluediamond" /></template>
