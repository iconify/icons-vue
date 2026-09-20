<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moh13gbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moh13gbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:messages-fill" /></template>
