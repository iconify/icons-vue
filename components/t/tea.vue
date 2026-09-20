<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu814jo0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xu814jo0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:tea" /></template>
