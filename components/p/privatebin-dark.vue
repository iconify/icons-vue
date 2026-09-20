<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhgbo5bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nhgbo5bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:privatebin-dark" /></template>
