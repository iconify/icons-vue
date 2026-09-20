<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-71aubjb.css';
import '../../css/v/v9pw7wbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h-71aubjb"/><path class="v9pw7wbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sonarr-radarr-light" /></template>
