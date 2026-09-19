<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxnb46bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cxnb46bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:radio-unchecked" /></template>
