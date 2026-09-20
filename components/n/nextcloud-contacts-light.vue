<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6d9_xu_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i6d9_xu_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-contacts-light" /></template>
