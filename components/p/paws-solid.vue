<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyskdjb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zyskdjb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:paws-solid" /></template>
