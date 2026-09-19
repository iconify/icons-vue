<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bva-u7fvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="bva-u7fvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:u1faaa-small" /></template>
