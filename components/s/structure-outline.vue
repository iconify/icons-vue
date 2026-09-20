<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze80w9uou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ze80w9uou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:structure-outline" /></template>
