<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7pma5bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w7pma5bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-wearing-helmet-paddling-kayak-on-water" /></template>
