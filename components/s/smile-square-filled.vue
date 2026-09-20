<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6hedybii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m6hedybii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:smile-square-filled" /></template>
