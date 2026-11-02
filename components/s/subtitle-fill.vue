<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctc1llh8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctc1llh8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:subtitle-fill" /></template>
