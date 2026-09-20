<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8tvufbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v8tvufbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrows-up" /></template>
