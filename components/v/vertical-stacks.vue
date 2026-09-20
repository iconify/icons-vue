<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg1xs5bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jg1xs5bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:vertical-stacks" /></template>
