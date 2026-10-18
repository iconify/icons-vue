<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tplzecbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tplzecbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:paintbrush" /></template>
