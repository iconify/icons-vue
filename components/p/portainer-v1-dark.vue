<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykk0mwkhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ykk0mwkhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:portainer-v1-dark" /></template>
