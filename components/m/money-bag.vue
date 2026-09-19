<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg7r8vz2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fg7r8vz2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:money-bag" /></template>
