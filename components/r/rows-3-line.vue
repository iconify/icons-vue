<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgwe686nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgwe686nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rows-3-line" /></template>
