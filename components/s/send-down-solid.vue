<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufkxafb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ufkxafb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:send-down-solid" /></template>
