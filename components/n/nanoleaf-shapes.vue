<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy5p4lb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy5p4lb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-shapes" /></template>
