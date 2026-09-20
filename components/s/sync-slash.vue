<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhtk0wbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhtk0wbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:sync-slash" /></template>
