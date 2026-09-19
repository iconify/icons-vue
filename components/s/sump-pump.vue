<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apx8kl_5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apx8kl_5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sump-pump" /></template>
