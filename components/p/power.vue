<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nymrah1gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-2.5};
const content = `<path class="nymrah1gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:power" /></template>
