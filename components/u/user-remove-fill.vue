<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b66zanxhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b66zanxhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-remove-fill" /></template>
