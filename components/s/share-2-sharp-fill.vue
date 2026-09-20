<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjmcl9b0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjmcl9b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:share-2-sharp-fill" /></template>
