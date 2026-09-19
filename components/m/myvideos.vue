<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3tby64at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":896};
const content = `<path class="v3tby64at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:myvideos" /></template>
