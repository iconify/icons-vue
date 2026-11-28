<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im4z9ha3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im4z9ha3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:stamp-x" /></template>
