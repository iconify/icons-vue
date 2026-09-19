<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4vq98bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4vq98bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:more" /></template>
