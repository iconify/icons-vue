<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa_5deg5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa_5deg5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:upload-lock-outline" /></template>
