<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc0bsybnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jc0bsybnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-right-beside-gas-flame" /></template>
