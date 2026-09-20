<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa_2v2l-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa_2v2l-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:times-light" /></template>
