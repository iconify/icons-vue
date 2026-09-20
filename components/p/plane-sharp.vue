<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-6ekh5os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-6ekh5os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:plane-sharp" /></template>
