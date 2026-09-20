<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmrndwx7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-1.5};
const content = `<path class="kmrndwx7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:transgender" /></template>
