<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csv4lubho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csv4lubho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:social-flickr-circular" /></template>
