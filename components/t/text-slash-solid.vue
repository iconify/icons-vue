<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsg_f3idp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsg_f3idp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:text-slash-solid" /></template>
