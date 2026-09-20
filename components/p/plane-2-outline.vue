<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq3ncxbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gq3ncxbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plane-2-outline" /></template>
