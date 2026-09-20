<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhzt1fb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhzt1fb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:notes-outline" /></template>
