<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1a2q6beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="v1a2q6beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:nav-icon-grid" /></template>
