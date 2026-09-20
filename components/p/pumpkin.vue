<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4ad55zzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v4ad55zzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pumpkin" /></template>
