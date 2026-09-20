<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crx6jyhul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crx6jyhul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:pen-nib-solid" /></template>
