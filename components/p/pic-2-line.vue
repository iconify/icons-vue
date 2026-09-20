<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbdsq-yur.css';
import '../../css/w/w22rijbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbdsq-yur"/><path class="w22rijbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pic-2-line" /></template>
