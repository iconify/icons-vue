<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m87ck961u.css';
import '../../css/d/d1brjbccy.css';
import '../../css/d/d-xbejb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m87ck961u"/><path class="d1brjbccy"/><path class="d-xbejb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:music-note" /></template>
