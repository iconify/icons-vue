<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdopu7blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdopu7blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:screen-4k-filled" /></template>
