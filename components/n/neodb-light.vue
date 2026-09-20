<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4-wo40im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g4-wo40im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:neodb-light" /></template>
