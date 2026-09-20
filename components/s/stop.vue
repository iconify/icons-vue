<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idf471b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="idf471b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:stop" /></template>
