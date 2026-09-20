<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihhhvcbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ihhhvcbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:stardust" /></template>
