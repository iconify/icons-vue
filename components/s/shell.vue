<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um4-w3bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um4-w3bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:shell" /></template>
