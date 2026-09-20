<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa1jqjb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"top":-3};
const content = `<path class="sa1jqjb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:tags" /></template>
