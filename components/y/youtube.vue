<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akt15xbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akt15xbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:youtube" /></template>
