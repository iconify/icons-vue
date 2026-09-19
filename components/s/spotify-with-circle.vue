<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be88_obth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="be88_obth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:spotify-with-circle" /></template>
