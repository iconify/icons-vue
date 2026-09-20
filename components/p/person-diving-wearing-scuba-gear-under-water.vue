<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfe-pzb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zfe-pzb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-diving-wearing-scuba-gear-under-water" /></template>
