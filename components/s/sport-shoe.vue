<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gznn9sbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gznn9sbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:sport-shoe" /></template>
