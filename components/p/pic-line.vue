<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvsatfkmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvsatfkmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pic-line" /></template>
