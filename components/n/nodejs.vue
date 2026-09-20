<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dope4ccwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dope4ccwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:nodejs" /></template>
