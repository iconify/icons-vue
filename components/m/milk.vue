<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzp_ikb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzp_ikb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:milk" /></template>
