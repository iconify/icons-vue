<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be5dz-b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="be5dz-b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:navigation-arrow-north-solid" /></template>
