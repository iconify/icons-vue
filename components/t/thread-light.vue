<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5f-hr--n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t5f-hr--n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:thread-light" /></template>
