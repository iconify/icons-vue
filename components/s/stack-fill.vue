<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-e__b-8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-e__b-8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:stack-fill" /></template>
