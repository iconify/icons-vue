<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anyfb0g-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anyfb0g-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:turn-right-up" /></template>
