<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns2ynsrwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ns2ynsrwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sim-outline" /></template>
