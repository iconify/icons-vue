<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqy61zbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cqy61zbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:michigan-lower-peninsula" /></template>
