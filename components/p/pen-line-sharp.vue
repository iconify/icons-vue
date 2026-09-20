<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re2qfhbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re2qfhbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pen-line-sharp" /></template>
