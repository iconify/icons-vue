<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uumr8ibws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uumr8ibws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:social-off" /></template>
