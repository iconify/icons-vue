<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgzons1xc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="jgzons1xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:people-roof" /></template>
