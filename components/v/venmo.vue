<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scz9fkbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scz9fkbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:venmo" /></template>
