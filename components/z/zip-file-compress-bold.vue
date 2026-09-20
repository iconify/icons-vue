<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx9a00_2h.css';
import '../../css/d/drkyq1beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx9a00_2h"/><path class="drkyq1beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:zip-file-compress-bold" /></template>
