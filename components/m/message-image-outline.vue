<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-m7ju5pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-m7ju5pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-image-outline" /></template>
