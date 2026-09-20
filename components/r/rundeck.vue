<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7jh_uzap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g7jh_uzap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rundeck" /></template>
