<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5akpe2ze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="w5akpe2ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:steaming-bowl" /></template>
