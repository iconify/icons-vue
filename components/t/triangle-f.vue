<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4vcqabxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="s4vcqabxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:triangle-f" /></template>
