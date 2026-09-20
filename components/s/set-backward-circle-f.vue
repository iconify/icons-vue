<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lya8juk5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="lya8juk5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:set-backward-circle-f" /></template>
