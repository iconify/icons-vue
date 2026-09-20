<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbmu0ac8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rbmu0ac8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:menu-square-filled" /></template>
