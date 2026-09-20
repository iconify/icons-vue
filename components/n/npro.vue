<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbdh6-b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cbdh6-b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:npro" /></template>
