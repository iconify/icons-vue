<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8yeqvbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8yeqvbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate-color:pinterest-logo" /></template>
