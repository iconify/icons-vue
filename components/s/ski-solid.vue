<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd52webnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd52webnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ski-solid" /></template>
