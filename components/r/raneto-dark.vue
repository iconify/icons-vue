<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmrs3xb8n.css';
import '../../css/g/gd6c7lbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bmrs3xb8n"/><path class="gd6c7lbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:raneto-dark" /></template>
