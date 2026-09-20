<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq0240abk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dq0240abk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:x-cross" /></template>
