<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_k-1tony.css';
import '../../css/j/jnok5972w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_k-1tony"/><path class="jnok5972w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:webhook-tester-light" /></template>
