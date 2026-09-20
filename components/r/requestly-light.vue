<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppee3vb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ppee3vb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:requestly-light" /></template>
