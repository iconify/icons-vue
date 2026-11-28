<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glmcx89ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glmcx89ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:meeting" /></template>
