<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ootzgdtft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ootzgdtft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:mask-solid" /></template>
