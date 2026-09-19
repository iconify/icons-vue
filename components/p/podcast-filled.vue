<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf9rmsdpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bf9rmsdpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:podcast-filled" /></template>
