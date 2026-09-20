<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-p29-bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k-p29-bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voux-dark" /></template>
