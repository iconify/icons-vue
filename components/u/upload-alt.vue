<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgwrju04h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgwrju04h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:upload-alt" /></template>
