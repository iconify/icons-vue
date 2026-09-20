<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au7sa78qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="au7sa78qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shop" /></template>
