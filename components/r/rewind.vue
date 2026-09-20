<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8p937b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="w8p937b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:rewind" /></template>
