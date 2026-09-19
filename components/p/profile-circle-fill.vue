<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg3ev6byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gg3ev6byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:profile-circle-fill" /></template>
