<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb5yemjxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xb5yemjxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:paperclip-small" /></template>
