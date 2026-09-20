<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfh8tn-5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gfh8tn-5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:scanner-solid" /></template>
