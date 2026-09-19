<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eulpmabae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eulpmabae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:remove-circle-sharp" /></template>
