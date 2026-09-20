<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv77d5bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="bv77d5bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:signin-solid" /></template>
