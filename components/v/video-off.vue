<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh5ygabzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh5ygabzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:video-off" /></template>
