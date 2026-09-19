<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvq6pj-fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":680};
const content = `<path class="yvq6pj-fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:tile" /></template>
