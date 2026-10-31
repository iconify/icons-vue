<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u80842buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u80842buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:view-split-solid" /></template>
