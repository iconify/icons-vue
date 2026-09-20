<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-a-20bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-a-20bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:test-tube-diagonal" /></template>
