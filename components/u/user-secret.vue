<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar5kgibhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ar5kgibhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:user-secret" /></template>
