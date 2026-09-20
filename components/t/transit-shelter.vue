<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqng2lb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gqng2lb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:transit-shelter" /></template>
