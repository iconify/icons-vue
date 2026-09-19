<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzzwzsb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzzwzsb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:rewind-right-fill" /></template>
