<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjz_34bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sjz_34bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:whatsapp-outline" /></template>
