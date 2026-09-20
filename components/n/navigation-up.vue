<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzn7e9_is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzn7e9_is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-up" /></template>
