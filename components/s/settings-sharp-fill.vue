<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vryog_buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vryog_buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:settings-sharp-fill" /></template>
