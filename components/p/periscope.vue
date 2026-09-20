<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amsw93bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="amsw93bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:periscope" /></template>
