<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my8pr8q6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="my8pr8q6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:passonce-light" /></template>
