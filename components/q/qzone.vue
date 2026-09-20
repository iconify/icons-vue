<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb2l4ubgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb2l4ubgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:qzone" /></template>
