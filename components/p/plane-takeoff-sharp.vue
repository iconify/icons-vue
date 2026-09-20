<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bin4q55ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bin4q55ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:plane-takeoff-sharp" /></template>
