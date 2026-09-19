<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp2bpywtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":703};
const content = `<path class="rp2bpywtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:paperboat" /></template>
