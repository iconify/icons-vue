<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_f4b-ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_f4b-ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:share" /></template>
