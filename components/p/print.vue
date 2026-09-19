<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv5412blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":683};
const content = `<path class="gv5412blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:print" /></template>
