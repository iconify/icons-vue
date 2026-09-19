<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey-b92b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ey-b92b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:share-sharp" /></template>
