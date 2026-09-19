<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9rsh3box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9rsh3box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:tag" /></template>
