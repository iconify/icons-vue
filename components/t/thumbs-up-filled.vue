<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkc4-e.css';
import '../../css/w/w3lddg.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-76.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkc4-e"/><path class="w3lddg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:thumbs-up-filled" /></template>
