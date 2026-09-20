<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1k5pbbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1k5pbbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:wikivoyage" /></template>
