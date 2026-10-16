<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etl048b3a.css';
import '../../css/a/alhm_84rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="etl048b3a"/><path class="alhm_84rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:route-20-bold" /></template>
