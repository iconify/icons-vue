<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c608vkkql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c608vkkql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:temperature-empty-fill" /></template>
