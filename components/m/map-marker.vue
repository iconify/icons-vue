<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa_i0o2ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="aa_i0o2ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:map-marker" /></template>
