<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-y1qabka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v-y1qabka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-contacts-light" /></template>
