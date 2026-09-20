<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eer8ncbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eer8ncbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ngc" /></template>
