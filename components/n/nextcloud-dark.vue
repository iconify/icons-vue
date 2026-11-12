<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxy3eibvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nxy3eibvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-dark" /></template>
