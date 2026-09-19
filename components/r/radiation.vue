<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxwc4vbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxwc4vbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:radiation" /></template>
