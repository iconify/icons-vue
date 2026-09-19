<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpzkiiujt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpzkiiujt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ventilator-alt-24px" /></template>
