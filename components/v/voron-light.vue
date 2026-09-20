<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9dv-pbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h9dv-pbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voron-light" /></template>
