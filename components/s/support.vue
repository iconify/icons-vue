<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de2mo0bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="de2mo0bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:support" /></template>
