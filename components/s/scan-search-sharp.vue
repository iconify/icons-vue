<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpe008b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpe008b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-search-sharp" /></template>
