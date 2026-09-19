<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8oj_3bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8oj_3bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:main-component" /></template>
