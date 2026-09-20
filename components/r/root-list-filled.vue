<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug0ko5b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug0ko5b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:root-list-filled" /></template>
