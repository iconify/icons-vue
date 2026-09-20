<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emz203hin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="emz203hin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:open-in-new-window" /></template>
