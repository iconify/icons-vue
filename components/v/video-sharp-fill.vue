<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpbypeasa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hpbypeasa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:video-sharp-fill" /></template>
