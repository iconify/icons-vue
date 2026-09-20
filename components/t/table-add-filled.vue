<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giu_owbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giu_owbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:table-add-filled" /></template>
