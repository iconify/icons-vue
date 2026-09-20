<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1nxihzgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1nxihzgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-text" /></template>
