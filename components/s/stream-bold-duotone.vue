<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn_f1tn5f.css';
import '../../css/d/ddsunemne.css';
import '../../css/h/htpdpeg8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn_f1tn5f"/><path class="ddsunemne"/><path class="htpdpeg8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stream-bold-duotone" /></template>
