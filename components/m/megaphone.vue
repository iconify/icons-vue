<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgdc1bbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgdc1bbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:megaphone" /></template>
