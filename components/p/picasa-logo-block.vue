<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i79c3zjsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i79c3zjsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:picasa-logo-block" /></template>
