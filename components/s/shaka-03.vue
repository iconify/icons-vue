<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbfxk0b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbfxk0b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shaka-03" /></template>
