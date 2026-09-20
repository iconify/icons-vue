<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sekj5jb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sekj5jb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:umbrella-off-sharp" /></template>
