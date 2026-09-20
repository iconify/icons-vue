<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_p24o3jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z_p24o3jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-feedback-heart-solid" /></template>
