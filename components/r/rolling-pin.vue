<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4yh3zb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4yh3zb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:rolling-pin" /></template>
