<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0m2_d1fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0m2_d1fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sofa-fill-round" /></template>
