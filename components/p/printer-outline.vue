<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br6gkkbnm.css';
import '../../css/y/y8r8-nbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br6gkkbnm"/><path clip-rule="evenodd" class="y8r8-nbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:printer-outline" /></template>
