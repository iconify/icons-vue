<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayicm5b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ayicm5b9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:pencil-2" /></template>
