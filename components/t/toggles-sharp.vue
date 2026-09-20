<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-_nxdr2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-_nxdr2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:toggles-sharp" /></template>
