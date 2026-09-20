<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1rw4pb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1rw4pb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:pause" /></template>
