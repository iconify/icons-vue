<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smrfk4eck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="smrfk4eck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:oksign" /></template>
