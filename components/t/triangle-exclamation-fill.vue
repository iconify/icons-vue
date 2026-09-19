<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwvz8v-kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xwvz8v-kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:triangle-exclamation-fill" /></template>
