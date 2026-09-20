<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djo0k6nzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="djo0k6nzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:play-small-solid" /></template>
