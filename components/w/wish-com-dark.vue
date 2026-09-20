<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxd672bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yxd672bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wish-com-dark" /></template>
