<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc6m9fbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc6m9fbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:package-fill" /></template>
