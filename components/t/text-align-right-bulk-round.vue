<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en9t1ybbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en9t1ybbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-align-right-bulk-round" /></template>
