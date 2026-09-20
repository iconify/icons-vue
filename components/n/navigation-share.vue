<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf61a3ufc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf61a3ufc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-share" /></template>
