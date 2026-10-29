<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2dultbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2dultbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:philippine-peso" /></template>
