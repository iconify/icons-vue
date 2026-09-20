<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8f-7w9qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v8f-7w9qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:routing" /></template>
