<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1a5oq34v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p1a5oq34v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:paper-clock-solid" /></template>
