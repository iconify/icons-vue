<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj4g1vdjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cj4g1vdjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:mouth-24px" /></template>
