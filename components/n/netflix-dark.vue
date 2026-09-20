<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq2kp497d.css';
import '../../css/k/krjjutbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wq2kp497d"/><path class="krjjutbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netflix-dark" /></template>
