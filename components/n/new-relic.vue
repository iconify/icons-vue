<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn9btkb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zn9btkb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:new-relic" /></template>
