<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as_ueqb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="as_ueqb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:people-above-pickup-truck" /></template>
