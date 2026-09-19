<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijzcvwbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ijzcvwbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:youko" /></template>
