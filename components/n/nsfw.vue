<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkxm5ccrh.css';
import '../../css/v/vsj2klbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkxm5ccrh"/><path class="vsj2klbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nsfw" /></template>
