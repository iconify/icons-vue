<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpt_1mb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lpt_1mb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:mask-20-solid" /></template>
