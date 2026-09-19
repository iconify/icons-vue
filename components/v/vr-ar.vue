<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz7oazmku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz7oazmku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:vr-ar" /></template>
