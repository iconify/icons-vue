<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uik8bmg6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="uik8bmg6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:more-vertical-solid" /></template>
