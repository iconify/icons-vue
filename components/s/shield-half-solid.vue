<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx7jcpb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx7jcpb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-half-solid" /></template>
