<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-532hvpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":24};
const content = `<path class="t-532hvpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:mobile" /></template>
