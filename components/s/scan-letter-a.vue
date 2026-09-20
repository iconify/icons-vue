<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezw_7jbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezw_7jbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:scan-letter-a" /></template>
