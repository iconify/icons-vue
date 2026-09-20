<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_js19b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_js19b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:the-sounds-resource" /></template>
