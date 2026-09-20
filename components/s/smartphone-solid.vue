<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgn5ezbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgn5ezbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:smartphone-solid" /></template>
