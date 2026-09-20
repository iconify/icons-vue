<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4yikcexh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n4yikcexh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:scale-filled" /></template>
