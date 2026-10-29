<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rix1rccmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rix1rccmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:salad" /></template>
