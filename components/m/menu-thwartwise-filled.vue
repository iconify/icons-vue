<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqwvn7bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qqwvn7bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:menu-thwartwise-filled" /></template>
