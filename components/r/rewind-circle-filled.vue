<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laxrx2gyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="laxrx2gyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rewind-circle-filled" /></template>
