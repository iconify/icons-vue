<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk5u0i5pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zk5u0i5pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:ranger-station-15" /></template>
