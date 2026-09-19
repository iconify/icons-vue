<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awxh1dbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="awxh1dbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:tags" /></template>
