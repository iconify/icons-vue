<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s63b25boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s63b25boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:qase" /></template>
