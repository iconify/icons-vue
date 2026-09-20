<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9-_hx82t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="w9-_hx82t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:tree" /></template>
