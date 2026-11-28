<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl7m9xbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl7m9xbgl primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:refresh-alert-duotone" /></template>
