<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wor4zrggg.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="wor4zrggg"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:thin-client-solid" /></template>
