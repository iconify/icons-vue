<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4cm7cbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4cm7cbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mouse-pointer-solid" /></template>
