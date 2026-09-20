<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b66p46a9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b66p46a9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:reader" /></template>
