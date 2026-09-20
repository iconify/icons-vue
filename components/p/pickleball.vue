<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh1r0w9jv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vh1r0w9jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:pickleball" /></template>
