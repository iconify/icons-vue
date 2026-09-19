<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byal_6bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byal_6bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:slack-solid" /></template>
