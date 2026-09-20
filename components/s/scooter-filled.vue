<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9-lygkzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9-lygkzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:scooter-filled" /></template>
