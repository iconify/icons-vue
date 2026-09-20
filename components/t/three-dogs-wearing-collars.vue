<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb9hgyngx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gb9hgyngx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-dogs-wearing-collars" /></template>
