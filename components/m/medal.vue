<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsw-e1bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gsw-e1bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:medal" /></template>
