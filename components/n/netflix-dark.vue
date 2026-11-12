<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq2kp497d.css';
import '../../css/c/c-9jnrbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wq2kp497d"/><path class="c-9jnrbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netflix-dark" /></template>
