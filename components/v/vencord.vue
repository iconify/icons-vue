<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrad-pw_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrad-pw_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vencord" /></template>
