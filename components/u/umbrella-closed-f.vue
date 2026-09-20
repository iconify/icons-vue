<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsg4ydbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-1.5};
const content = `<path class="nsg4ydbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:umbrella-closed-f" /></template>
