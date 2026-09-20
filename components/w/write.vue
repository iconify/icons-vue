<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx-k1mb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nx-k1mb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:write" /></template>
