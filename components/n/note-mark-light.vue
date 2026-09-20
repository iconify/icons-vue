<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqg31zb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xqg31zb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:note-mark-light" /></template>
