<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g91dgxblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g91dgxblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone-end2" /></template>
