<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc21h7bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc21h7bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sorting-center-light" /></template>
