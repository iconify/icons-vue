<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anv3f7brl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="anv3f7brl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:univention-corporate-server-light" /></template>
