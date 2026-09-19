<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow059ibzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ow059ibzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:piano" /></template>
