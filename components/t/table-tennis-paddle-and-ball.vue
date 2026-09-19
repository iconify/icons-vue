<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njo7p1bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="njo7p1bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:table-tennis-paddle-and-ball" /></template>
