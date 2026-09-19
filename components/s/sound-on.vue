<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnrwt8bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnrwt8bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:sound-on" /></template>
