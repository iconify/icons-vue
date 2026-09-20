<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amc34abky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1534,"height":1534};
const content = `<path class="amc34abky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wisetech-global-dark" /></template>
