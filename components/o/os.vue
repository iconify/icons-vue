<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a92uke88p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a92uke88p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:os" /></template>
