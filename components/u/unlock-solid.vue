<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrn2ykbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrn2ykbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:unlock-solid" /></template>
