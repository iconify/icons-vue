<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg9mmgber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="yg9mmgber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:plus-circle-o-duplicate" /></template>
