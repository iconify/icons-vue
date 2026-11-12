<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4s1fkb8q.css';
import '../../css/u/uvc30bbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v4s1fkb8q"/><path class="uvc30bbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openadserver-dark" /></template>
