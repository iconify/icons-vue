<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bogds5biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bogds5biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pixabay" /></template>
