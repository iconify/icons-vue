<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpf_jubge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpf_jubge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:volleyball" /></template>
