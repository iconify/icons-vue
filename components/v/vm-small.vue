<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2a315bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="p2a315bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:vm-small" /></template>
