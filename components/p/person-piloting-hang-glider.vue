<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg-9uhmgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qg-9uhmgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-piloting-hang-glider" /></template>
