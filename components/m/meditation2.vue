<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efoffhfdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="efoffhfdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:meditation2" /></template>
