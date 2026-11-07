<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-i4kgtbw.css';
import '../../css/t/tsgsm7xry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-i4kgtbw"/><path class="tsgsm7xry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-notes-bold-duotone" /></template>
