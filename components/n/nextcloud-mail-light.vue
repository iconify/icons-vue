<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy6gxbbso.css';
import '../../css/h/hdoub2b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vy6gxbbso"/><path class="hdoub2b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-mail-light" /></template>
