<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s665nnb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s665nnb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:opencritic" /></template>
