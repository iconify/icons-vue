<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymy-usqjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymy-usqjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:navigation-solid" /></template>
