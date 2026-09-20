<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6uc1hb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6uc1hb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:question-mark-square-fill" /></template>
