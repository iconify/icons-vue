<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e44evsbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e44evsbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:user-check-filled" /></template>
