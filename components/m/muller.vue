<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt5qu0bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt5qu0bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:muller" /></template>
