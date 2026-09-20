<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fho_u-6sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fho_u-6sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:social-unsplash-solid" /></template>
