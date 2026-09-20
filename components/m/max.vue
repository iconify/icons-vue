<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns09k3orw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ns09k3orw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:max" /></template>
