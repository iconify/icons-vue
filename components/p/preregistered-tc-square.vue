<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0-wepb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="a0-wepb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:preregistered-tc-square" /></template>
