<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fijs2gb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fijs2gb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:pentagon-top-left" /></template>
