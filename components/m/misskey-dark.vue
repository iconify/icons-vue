<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkvn_37ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pkvn_37ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:misskey-dark" /></template>
