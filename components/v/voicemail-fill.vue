<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u25rjsbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u25rjsbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:voicemail-fill" /></template>
