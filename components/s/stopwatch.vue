<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty7dgacra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ty7dgacra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:stopwatch" /></template>
