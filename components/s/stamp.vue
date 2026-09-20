<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xho3spb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xho3spb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:stamp" /></template>
