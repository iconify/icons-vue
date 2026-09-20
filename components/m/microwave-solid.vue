<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc0url8kw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bc0url8kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:microwave-solid" /></template>
