<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_28j75nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_28j75nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:toast-filled" /></template>
