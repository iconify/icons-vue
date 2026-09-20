<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjfwagpfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yjfwagpfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:package-dependents-16" /></template>
