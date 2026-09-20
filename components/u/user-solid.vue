<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgmkf8j1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgmkf8j1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:user-solid" /></template>
