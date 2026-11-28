<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq_mvabyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq_mvabyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:store-lock" /></template>
