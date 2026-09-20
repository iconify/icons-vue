<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfocj3bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfocj3bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:square-dashed-x-corner" /></template>
