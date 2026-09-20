<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moqid97xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moqid97xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:racket-ball" /></template>
