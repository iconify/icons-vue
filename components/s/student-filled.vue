<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilyzix5eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ilyzix5eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:student-filled" /></template>
