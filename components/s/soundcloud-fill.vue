<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejan3lbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejan3lbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:soundcloud-fill" /></template>
