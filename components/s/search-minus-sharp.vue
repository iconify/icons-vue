<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npd_bhh0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npd_bhh0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-minus-sharp" /></template>
