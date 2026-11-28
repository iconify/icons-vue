<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcp48hbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcp48hbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:three-fingers-solid" /></template>
