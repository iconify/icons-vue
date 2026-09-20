<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4kr_v9pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z4kr_v9pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:maintainerr-dark" /></template>
