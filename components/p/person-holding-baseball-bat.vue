<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn5-p75tj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mn5-p75tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-holding-baseball-bat" /></template>
