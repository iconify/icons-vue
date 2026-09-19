<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmih6vbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gmih6vbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:pineapple" /></template>
