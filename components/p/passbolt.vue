<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnepxqa4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnepxqa4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:passbolt" /></template>
