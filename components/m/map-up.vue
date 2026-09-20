<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbwfzrb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbwfzrb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-up" /></template>
