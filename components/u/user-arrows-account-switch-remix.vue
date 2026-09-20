<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssemfp7-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ssemfp7-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-arrows-account-switch-remix" /></template>
