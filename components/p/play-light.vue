<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uczwstkjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uczwstkjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:play-light" /></template>
