<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzuy0jr7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":9};
const content = `<path class="xzuy0jr7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:quote" /></template>
