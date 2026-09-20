<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3znd9b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n3znd9b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-calendar-light" /></template>
