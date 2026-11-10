<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n93l26b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n93l26b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:trash-x-mark-16-solid" /></template>
