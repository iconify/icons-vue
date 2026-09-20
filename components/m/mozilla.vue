<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twara5b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twara5b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mozilla" /></template>
