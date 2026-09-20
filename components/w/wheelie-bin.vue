<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wes71tvry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wes71tvry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wheelie-bin" /></template>
