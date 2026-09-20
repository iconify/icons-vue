<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0sc7siga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0sc7siga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mazda" /></template>
