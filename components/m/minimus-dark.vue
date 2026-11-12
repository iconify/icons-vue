<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr0pl4b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lr0pl4b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minimus-dark" /></template>
