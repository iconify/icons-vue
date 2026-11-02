<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c56zymbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c56zymbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:surprise-fill" /></template>
