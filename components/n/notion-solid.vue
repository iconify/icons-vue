<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cedirc54l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cedirc54l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:notion-solid" /></template>
