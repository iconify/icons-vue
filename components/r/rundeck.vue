<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqewi1k0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqewi1k0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rundeck" /></template>
