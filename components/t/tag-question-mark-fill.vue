<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiepgwb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiepgwb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:tag-question-mark-fill" /></template>
