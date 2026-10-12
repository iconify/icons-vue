<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z71u6ob1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z71u6ob1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-x-filled" /></template>
