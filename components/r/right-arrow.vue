<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkgwzph3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkgwzph3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:right-arrow" /></template>
