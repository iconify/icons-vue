<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwnt3j9zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwnt3j9zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:myob" /></template>
