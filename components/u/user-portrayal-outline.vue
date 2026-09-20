<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5ih2lb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x5ih2lb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:user-portrayal-outline" /></template>
