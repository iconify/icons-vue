<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic2trybrb.css';
import '../../css/y/yj8n5jbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ic2trybrb"/><path class="yj8n5jbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:umbrella-20" /></template>
