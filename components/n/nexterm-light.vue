<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a90eiubml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a90eiubml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nexterm-light" /></template>
