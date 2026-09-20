<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr9277r9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vr9277r9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:marpui" /></template>
