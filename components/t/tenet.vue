<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lez7u-jzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lez7u-jzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:tenet" /></template>
