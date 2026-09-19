<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agfd4ibou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="agfd4ibou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:vimeo" /></template>
