<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f95n9t5om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f95n9t5om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-small" /></template>
