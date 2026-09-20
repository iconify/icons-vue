<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-ay5zbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-ay5zbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:top-arrow-to-top" /></template>
