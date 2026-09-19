<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5i-kqbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m5i-kqbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:youtube-with-circle" /></template>
