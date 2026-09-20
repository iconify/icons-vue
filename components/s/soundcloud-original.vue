<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxo1zg92k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vxo1zg92k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:soundcloud-original" /></template>
