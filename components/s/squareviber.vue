<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4a4kabvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="c4a4kabvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squareviber" /></template>
