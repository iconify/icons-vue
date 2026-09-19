<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd9-2o1_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fd9-2o1_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-braces-filled" /></template>
