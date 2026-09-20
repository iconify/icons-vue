<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9xzdwbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1534,"height":1534};
const content = `<path class="q9xzdwbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wisetech-global" /></template>
