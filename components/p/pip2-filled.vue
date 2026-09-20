<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glhuh6byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="glhuh6byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pip2-filled" /></template>
