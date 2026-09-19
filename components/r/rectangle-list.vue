<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye8rm259n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ye8rm259n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:rectangle-list" /></template>
