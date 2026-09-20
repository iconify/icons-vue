<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9be7jb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9be7jb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-horizontal-fill" /></template>
