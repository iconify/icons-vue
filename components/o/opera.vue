<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa_537b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2};
const content = `<path class="oa_537b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:opera" /></template>
