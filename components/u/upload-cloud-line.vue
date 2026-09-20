<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyt5i2b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyt5i2b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:upload-cloud-line" /></template>
