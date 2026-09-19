<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3-m1jbcu.css';
import '../../css/q/q45ggwbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3-m1jbcu"/><path class="q45ggwbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:shopping-bags" /></template>
