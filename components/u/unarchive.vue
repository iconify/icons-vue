<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-f-t6bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-f-t6bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:unarchive" /></template>
