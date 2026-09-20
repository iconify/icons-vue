<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu--34z8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iu--34z8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:track-previous" /></template>
