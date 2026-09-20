<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozvdwcc6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ozvdwcc6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:send-square-filled" /></template>
