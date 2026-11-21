<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5genbbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5genbbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:storefront-outline" /></template>
