<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4j0rxb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4j0rxb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panels-right-bottom-sharp" /></template>
