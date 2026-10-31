<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcgi_3evl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcgi_3evl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paragraph-bulk-round" /></template>
