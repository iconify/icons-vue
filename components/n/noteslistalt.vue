<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz5-0vghi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sz5-0vghi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:noteslistalt" /></template>
