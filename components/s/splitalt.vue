<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8ft-ub9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1025};
const content = `<path class="c8ft-ub9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:splitalt" /></template>
