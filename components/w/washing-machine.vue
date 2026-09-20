<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok_5v3ylq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ok_5v3ylq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:washing-machine" /></template>
