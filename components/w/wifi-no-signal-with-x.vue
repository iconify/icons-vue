<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxgrxpsyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cxgrxpsyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wifi-no-signal-with-x" /></template>
