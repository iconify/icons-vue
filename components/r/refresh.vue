<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi4pqkbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi4pqkbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:refresh" /></template>
