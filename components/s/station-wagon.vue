<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvfgu0lvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tvfgu0lvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:station-wagon" /></template>
