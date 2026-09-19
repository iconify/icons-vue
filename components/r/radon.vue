<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gryfkac7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gryfkac7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:radon" /></template>
