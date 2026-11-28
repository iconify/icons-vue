<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju6kvy1jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju6kvy1jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-power-solid" /></template>
