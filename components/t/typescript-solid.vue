<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipqw2w6vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ipqw2w6vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:typescript-solid" /></template>
