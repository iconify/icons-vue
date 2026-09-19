<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3u3rrbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3u3rrbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:vaccine-protection-wash-hands" /></template>
