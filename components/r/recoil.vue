<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beynuj9wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beynuj9wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:recoil" /></template>
