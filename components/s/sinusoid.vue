<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0n990bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v0n990bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sinusoid" /></template>
