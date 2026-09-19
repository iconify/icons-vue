<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj_3yzbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj_3yzbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:trash-bin-outline" /></template>
