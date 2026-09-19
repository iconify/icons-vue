<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2cs58beo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="o2cs58beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:script" /></template>
