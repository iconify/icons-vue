<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cydehgbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cydehgbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:penis-alt-24px" /></template>
