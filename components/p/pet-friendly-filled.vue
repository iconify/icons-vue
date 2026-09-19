<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8am-97fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c8am-97fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:pet-friendly-filled" /></template>
