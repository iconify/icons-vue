<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tec9y_bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tec9y_bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ranger-hat" /></template>
