<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9fcrsv2i.css';
import '../../css/g/gke_r-j4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-shadow x9fcrsv2i"/><path class="gke_r-j4g wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:menu" /></template>
