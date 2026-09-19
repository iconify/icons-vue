<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpl03kbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lpl03kbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:nuclear" /></template>
