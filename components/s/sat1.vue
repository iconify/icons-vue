<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8grcmjgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8grcmjgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sat1" /></template>
