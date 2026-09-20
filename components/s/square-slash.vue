<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yazcnkqnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yazcnkqnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-slash" /></template>
