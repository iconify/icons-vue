<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9ob-jvxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9ob-jvxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:signal-full" /></template>
