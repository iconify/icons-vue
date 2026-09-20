<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9s53f24b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9s53f24b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-bottom-close-sharp" /></template>
