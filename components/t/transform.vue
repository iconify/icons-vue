<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwnz6elst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cwnz6elst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:transform" /></template>
