<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af9nscbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af9nscbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paper-bag-sharp" /></template>
