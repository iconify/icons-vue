<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsb86qbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="wsb86qbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:person" /></template>
