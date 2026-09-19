<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaa6_29ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iaa6_29ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:package" /></template>
