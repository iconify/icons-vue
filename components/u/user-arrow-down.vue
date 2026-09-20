<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd-hh9b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd-hh9b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-arrow-down" /></template>
