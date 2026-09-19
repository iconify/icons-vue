<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykg2bgbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ykg2bgbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:thunderbolt-fill" /></template>
