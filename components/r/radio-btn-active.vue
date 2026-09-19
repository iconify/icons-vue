<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb-tdob4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb-tdob4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:radio-btn-active" /></template>
