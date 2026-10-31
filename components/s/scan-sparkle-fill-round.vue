<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5v1dn0pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5v1dn0pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-sparkle-fill-round" /></template>
